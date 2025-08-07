# 🚢 Titanic Survival Prediction - EDA

This project is an **Exploratory Data Analysis (EDA)** on the classic **Titanic Dataset**. The goal is to understand the data and explore patterns that may explain survival outcomes.

## 📂 Dataset

The Titanic dataset contains information about the passengers aboard the Titanic, including:

- **PassengerId** – Unique ID for each passenger  
- **Survived** – Target variable (0 = No, 1 = Yes)  
- **Pclass** – Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)  
- **Name**, **Sex**, **Age**, **SibSp**, **Parch** – Demographics and family info  
- **Ticket**, **Fare**, **Cabin**, **Embarked** – Travel-related features

## 🎯 Project Objectives

- Understand the structure of the dataset
- Handle missing values and data cleaning
- Perform univariate and bivariate analysis
- Visualize key relationships between features and survival
- Identify potential patterns and trends that influence survival

## 📊 Key Questions

- Who were more likely to survive? (e.g., women, children, 1st class passengers)
- Does passenger class or fare have a significant impact on survival?
- Are there any correlations between age and survival?
- What can we learn from embarked location?

## 🛠️ Libraries & Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 📌 Key Findings

- Female passengers had a significantly higher survival rate.
- First class passengers had a better chance of survival than second and third class.
- Younger passengers were slightly more likely to survive.
- Embarked location also showed slight variation in survival rates.

## 📝 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/titanic-eda.git
