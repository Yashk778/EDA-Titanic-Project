# Titanic Survival Prediction – Machine Learning 

**Objective:**  
Predict survival of passengers on the Titanic using Machine Learning.



##  Steps

### 1. Data Exploration (EDA)
- Performed univariate and multivariate analysis using plots.  
- Observed survival trends across features like `Pclass`, `Age`, `Fare`, and `Sex`.

### 2. Feature Engineering
- Created **Family Size** = `SibSp + Parch + 1`  
- Created **Known Cabin** (1 if Cabin is known, 0 otherwise)  
- Grouped **Age** into categories for analysis  

### 3. Handling Missing Values
- Used **SimpleImputer** for numeric columns (median)  
- Used most frequent strategy or custom handling for categorical columns  

### 4. Encoding Categorical Features
- Converted categorical columns (`Sex`, `Embarked`) into numeric format using **OneHotEncoder**  

### 5. Preprocessing & Pipeline
- Built a **Pipeline** including imputation and scaling  
- Ensures reproducible preprocessing for any model  

### 6. Model Training & Evaluation
- Compared **Logistic Regression**, **Decision Tree**, and **Random Forest**  
- Evaluated with **10-fold cross-validation**  
- Best model: **Logistic Regression (~80% accuracy)**  

### 7. Performance Metrics
- Confusion Matrix, Precision, Recall, F1-score  
- Logistic Regression had better balance between predicting survivors and non-survivors  

---

## Results
- Accuracy: ~80%  
- Model successfully identifies the majority of survivors and non-survivors  
- Example Confusion Matrix:


## 🛠 Tools & Libraries

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook
-scikit-learn
##Files Included

- `Titanic_Disaster.ipynb` – Jupyter notebook with full analysis
- `train_set.csv & test_set.csv` – Dataset used




