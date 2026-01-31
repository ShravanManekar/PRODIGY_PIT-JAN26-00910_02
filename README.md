# 🚢 Titanic Data Cleaning & Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on performing **data cleaning and exploratory data analysis (EDA)** on the Titanic dataset. The objective is to understand the dataset structure, handle missing values, explore relationships between variables, and identify key patterns and trends that influenced passenger survival.

This task is part of **Task 2 – Data Cleaning and EDA** for the internship project.

---

## 📂 Dataset Information

The dataset used is the **Titanic dataset**, which contains information about passengers onboard the Titanic.

**Files used:**

* `train.csv` – Main dataset containing features and the target variable (`Survived`)
* `test.csv` – Dataset without target variable (not used for EDA)
* `gender_submission.csv` – Sample submission file

**Source:**
Prodigy InfoTech – Data Science Datasets (Task 2)

---

## 🧹 Data Cleaning Steps

The following preprocessing steps were performed:

* Identified missing values in the dataset
* Filled missing `Age` values using the median
* Filled missing `Embarked` values using the mode
* Dropped the `Cabin` column due to excessive missing data
* Converted categorical variables into numerical format
* Applied one-hot encoding for categorical features

---

## 📊 Exploratory Data Analysis (EDA)

EDA was performed to understand data distribution and relationships using visualizations such as:

* Survival count distribution
* Survival rate by gender
* Survival rate by passenger class
* Age and fare distribution by survival status
* Survival analysis based on family size (`SibSp`, `Parch`)
* Correlation heatmap of numerical features

---

## 🔍 Key Insights

* Female passengers had a significantly higher survival rate than males
* First-class passengers were more likely to survive
* Younger passengers showed higher survival chances
* Higher ticket fares were associated with better survival probability
* Passengers traveling with small families had better survival rates
* Gender and passenger class were the strongest predictors of survival

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📁 Project Structure

```
├── train.csv
├── test.csv
├── gender_submission.csv
├── titanic_eda.ipynb
└── README.md
```

---

## ✅ Conclusion

This project demonstrates effective data cleaning techniques and insightful exploratory data analysis. The findings help in understanding the factors affecting survival and prepare the dataset for future machine learning modeling.

---

⭐ If you found this project helpful, feel free to star the repository!
