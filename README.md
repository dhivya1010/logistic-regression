# 🚢 Titanic Survival Prediction using Logistic Regression

This project explores the **Titanic dataset** to predict passenger survival using **Logistic Regression**, a fundamental classification algorithm in machine learning. It includes data preprocessing, exploratory analysis, model building, evaluation, and visualization.

---


---

## 🎯 Objective

To build a **Logistic Regression model** that predicts whether a passenger survived the Titanic disaster based on features like:
- Age
- Sex
- Passenger Class (Pclass)
- Fare
- Embarked location
- Family size (SibSp + Parch)

---

## 🧾 Dataset Details

- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- **Features**:
  - `PassengerId`, `Name`, `Sex`, `Age`, `Pclass`, `SibSp`, `Parch`, `Fare`, `Embarked`, `Survived` (target)

---

## 🧪 Technologies Used

- Python
- Pandas
- NumPy
- Seaborn & Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## ⚙️ Workflow

1. **Data Cleaning**
   - Handling missing values (Age, Embarked)
   - Encoding categorical variables (Sex, Embarked)
2. **Exploratory Data Analysis (EDA)**
   - Survival rate by gender, class, and age groups
   - Correlation matrix
3. **Feature Engineering**
   - Creating new features like `FamilySize`
4. **Modeling**
   - Train-test split (80/20)
   - Logistic Regression training
   - Evaluation: Accuracy, Precision, Recall, F1 Score, Confusion Matrix
5. **Visualization**
   - Confusion matrix heatmap
   - ROC curve (optional)

---

## 📈 Results

- **Model Accuracy**: `~80%` (adjust based on your actual result)
- **Insights**:
  - Females had significantly higher survival rates
  - Passengers in 1st class had better chances of survival
  - Younger passengers had a slightly higher survival probability

---





