#  Data Dictionary - Titanic Dataset

##  Original Features

* **PassengerId** = Unique identifier for each passenger
* **Survived** = Survival status (0 = No, 1 = Yes)
* **Pclass** = Passenger class (1 = First, 2 = Second, 3 = Third)
* **Name** = Full name of the passenger
* **Sex** = Gender (male, female)
* **Age** = Age in years
* **SibSp** = Number of siblings/spouses aboard
* **Parch** = Number of parents/children aboard
* **Ticket** = Ticket number
* **Fare** = Passenger fare
* **Cabin** = Cabin number
* **Embarked** = Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

---

##  Engineered Features

* **FamilySize** = Total family members aboard (SibSp + Parch + 1)
* **IsAlone** = Indicates if passenger is alone (1 = Yes, 0 = No)
* **Title** = Extracted title from passenger name (e.g., Mr, Mrs, Miss, Master, Rare)

---

##  Encoded Features

* **Sex** = Gender encoded (0 = Male, 1 = Female)

* **Embarked_Q** = Passenger embarked from Queenstown (1 = Yes, 0 = No)

* **Embarked_S** = Passenger embarked from Southampton (1 = Yes, 0 = No)

* **Title_Miss** = Passenger title is Miss

* **Title_Mr** = Passenger title is Mr

* **Title_Mrs** = Passenger title is Mrs

* **Title_Rare** = Passenger has a rare title

---

##  Removed Features

* **Name** = Removed after extracting Title
* **Ticket** = Removed due to low predictive value
* **Cabin** = Removed due to high number of missing values
* **PassengerId** = Removed during modeling as it is a unique identifier and does not carry predictive information for survival. 


---

##  Notes

* Categorical variables were encoded to be used in machine learning models
* Feature engineering was applied to improve predictive performance
* Final dataset used for modeling: `titanic_featured.csv`

