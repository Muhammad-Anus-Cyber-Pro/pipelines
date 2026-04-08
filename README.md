# Titanic ML Project: With vs Without Pipelines

This project demonstrates the implementation of Machine Learning workflows on the Titanic dataset, comparing **manual preprocessing** with **Pipeline-based approach**.

---

## 📂 Dataset

- Dataset: Titanic
- Target Variable: `Survived`
- Features include:
  - Age
  - Sex
  - Embarked
  - Pclass
  - Fare

---

## ⚙️ Project Workflow

### 🔹 Approach 1: Without Pipeline

- Handled missing values using `SimpleImputer`
- Applied encoding manually (`OneHotEncoder, MinMaxScaler`)
- Performed transformations step-by-step
- Trained model separately

❗ Challenges:
- Code becomes lengthy and repetitive  
- Higher risk of data leakage  
- Hard to maintain and scale  

---

### 🔹 Approach 2: With Pipeline

- Used:
  - `ColumnTransformer`
  - `Pipeline`
- Combined:
  - Imputation
  - Encoding
  - Model training in one workflow

✅ Benefits:
- Cleaner and structured code  
- Prevents data leakage  
- Easier to deploy in real-world applications  

---

## 🧠 Model Used

- DecisionTreeClassifier

---

## 📊 Results & Observations

- Both approaches achieved similar performance
- Pipeline approach was:
  - More efficient  
  - More readable  
  - More production-friendly  

---

## 🚀 Key Learnings

- Importance of pipelines in ML workflows  
- Difference between manual preprocessing and automated pipelines  
- Avoiding data leakage using proper techniques  

---

## 📦 Libraries Used

- numpy  
- pandas  
- matplotlib  
- scikit-learn  

---

## 🔮 Future Work

- Hyperparameter tuning using GridSearchCV with Pipeline  
- Deployment using Flask/Streamlit  
- Advanced feature engineering  

---
