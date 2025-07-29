# EDA-Titanic-Project
# Titanic Survival Exploration – EDA Project

This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset to understand patterns in passenger survival. It is my first hands-on EDA project, done as part of my data science learning journey.

##Dataset

The dataset used is the famous [Titanic dataset](https://www.kaggle.com/c/titanic/data), containing information about passengers aboard the Titanic, including features like:

- Name, Age, Sex
- Passenger Class (Pclass)
- Fare, Embarked port
- Number of siblings/spouses (SibSp)
- Number of parents/children (Parch)
- Survival status (0 = No, 1 = Yes)

## Analysis Performed

The project includes:

###🔹1. Data Loading & Cleaning
- Loaded dataset and checked for null values
- Cleaned missing data (Age, Embarked, etc.)
- Created new feature: `FamilySize` = `SibSp + Parch + 1`

###🔹2. Univariate Analysis
- Distribution of Age and Fare (histplots)
- Countplots for Sex, Pclass, and Family Size

###🔹3. Bivariate Analysis
- Survival rates by Sex and Pclass
- Age group survival comparison
- Fare vs Survival (violin plot)

###🔹4. Multivariate Analysis
- Countplot of Sex and Pclass with Survival hue
- Catplot combining multiple features

##  Key Insights

- **Females had a higher survival rate** than males.
- **First class passengers were more likely to survive**.
- **Younger age groups had higher survival chances**.
- Family size had a slight effect on survival probability.

## 🛠 Tools & Libraries

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook

##Files Included

- `EDA-project.ipynb` – Jupyter notebook with full analysis
- `Titanic.csv` – Dataset used

## Future Work

- Apply machine learning models for survival prediction
- Handle missing data with imputation
- Feature engineering for Name/Title, Cabin, etc.

---



