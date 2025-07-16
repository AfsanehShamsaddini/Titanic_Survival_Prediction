# 🚢 Titanic Survival Prediction

Predicting survival outcomes from the Titanic disaster using machine learning and statistical analysis.

## 🎯 Objective
This project aims to predict whether a passenger survived the Titanic shipwreck based on features like age, gender, ticket class, and fare. Understanding survival patterns has educational value and demonstrates real-world binary classification.

## 📊 Dataset
- Source: [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic)
- Features include:
  - `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`, etc.
  - Target variable: `Survived` (0 = No, 1 = Yes)

## 🔍 Methodology
- **Data Preprocessing**: Handling missing values, encoding categorical variables, feature selection
- **Exploratory Data Analysis**: Visualizations and correlation analysis
- **Feature Engineering**: Extracting titles, grouping ages, and creating new features
- **Hypothesis Testing**:
  - Chi-Square test performed to check dependency between `Sex` and `Survived`
  - Result: Strong statistical evidence that survival was significantly dependent on gender
- **Modeling**: Logistic Regression & other classifiers
- **Evaluation**: Accuracy, precision, recall, F1-score, confusion matrix

## 📈 Results
- The model shows that gender was a strong predictor of survival.
- Logistic Regression performed well with interpretable coefficients.

## 📚 Libraries Used
- pandas, numpy, matplotlib, seaborn, scikit-learn, scipy

## ✅ Conclusion
Gender plays a key role in survival. Females had a significantly higher survival rate, confirmed by both EDA and hypothesis testing.

## 📁 How to Run
1. Clone the repo
2. Install dependencies
3. Run `Titanic_Survival_Prediction.ipynb`

---

**Author:** Afsaneh Shamsaddini


