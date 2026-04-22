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


##  Results

The model achieved strong predictive performance on the Titanic dataset:

* Model: Random Forest Classifier
* Validation Method: Train/Test Split
* Accuracy: ~0.84

---

##  Conclusion

This project demonstrates the impact of proper data preprocessing and feature engineering on model performance.

Key takeaways:

* Feature engineering (such as FamilySize and Title extraction) significantly improved results
* Gender and passenger class are strong predictors of survival
* A well-structured pipeline can achieve high performance even without complex models

The final accuracy of ~0.84 highlights the effectiveness of the approach and the quality of the data preparation process.

---

##  Author

Fernando Leite

Aspiring Data Scientist focused on building real-world data projects and continuously improving analytical and machine learning skills.

