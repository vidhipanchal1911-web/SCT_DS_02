# Titanic Survival Analysis - Exploratory Data Analysis (EDA)

## 📖 Project Overview
This project is an exploratory data analysis of the classic Titanic dataset from Kaggle. The goal was to practice data cleaning, data visualization, and uncover insights into the factors that influenced passenger survival during the disaster. This was completed as Task 1 during my internship at **Skill Craft Technology**.

---

## 📊 Dataset
The dataset used is the `train.csv` file from the [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data). It contains information about individual passengers, such as their age, gender, passenger class, and whether they survived.

---

## 🛠️ Tools & Libraries
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Google Colab

---

## 📈 Analysis & Findings
The analysis process involved several key steps:
1.  **Data Cleaning:** Handled missing values in the `Age` and `Embarked` columns and removed irrelevant columns like `Cabin`.
2.  **Univariate Analysis:** Explored the distribution of individual features like age, gender, and passenger class.
3.  **Bivariate Analysis:** Investigated the relationship between different features and the survival outcome.

### Key Findings:
* **Gender:** Females had a significantly higher survival rate (around 74%) compared to males (around 19%).
* **Passenger Class:** First-class passengers had a much higher chance of survival (over 62%) than third-class passengers (24%).
* **Age:** Children under the age of 10 had a notably higher survival rate than other age groups.

---

## 🚀 How to Run
1. Clone this repository to your local machine.
2. Ensure you have the required libraries installed (`pandas`, `seaborn`, etc.).
3. Open the `.ipynb` notebook file in a Jupyter environment or Google Colab and run the cells.
