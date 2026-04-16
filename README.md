#  Titanic Survival Analysis

##  Objective

The goal of this project is to analyze the Titanic dataset and build a machine learning model capable of predicting passenger survival.

This project follows a complete end-to-end data science pipeline, from raw data to model evaluation.

---

##  Project Overview

The workflow is divided into four main stages:

* **Data Cleaning**
  Handling missing values, removing unnecessary columns, and preparing the dataset

* **Exploratory Data Analysis (EDA)**
  Understanding patterns, distributions, and relationships between variables

* **Feature Engineering**
  Creating new features such as:

  * FamilySize
  * IsAlone
  * Title extraction from names

* **Modeling**
  Training a machine learning model to predict survival

---

##  Key Insights

* Gender is one of the most important factors — females had significantly higher survival rates
* Passenger class strongly influenced survival probability
* Family size impacts survival — small groups had better outcomes
* Social status (captured through titles) plays a relevant role

---

##  Model Performance

* Model used: **Random Forest Classifier**
* Validation approach: Train/Test Split
* The model achieved a solid performance, indicating meaningful patterns in the data

---

##  Project Structure

```
titanic-survival-analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_feature_engineering.ipynb
│   └── 04_modeling.ipynb
│
├── kaggle/
│   └── titanic_kaggle.ipynb
│
├── README.md
└── data_dictionary.md
```

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Seaborn
* Matplotlib

---

##  Next Steps

* Improve model performance with more advanced algorithms
* Apply hyperparameter tuning
* Explore additional feature engineering techniques

---

##  Author

Fernando Leite

Aspiring Data Scientist focused on building real-world data projects and continuously improving analytical and machine learning skills.

