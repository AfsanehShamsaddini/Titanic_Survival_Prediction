Titanic Survival Prediction Using Machine Learning
Importing Libraries
In this project, I utilize essential libraries to enhance data manipulation and visualization:

pandas: For data manipulation and analysis of tabular data.
numpy: For efficient numerical computations.
seaborn: To create informative statistical graphics.
matplotlib.pyplot: For plotting and visualizing data and analysis results.
Loading Data
The project begins with loading the dataset from CSV files into pandas DataFrames, splitting the data into training and testing sets. These datasets contain vital information about Titanic passengers, laying the foundation for analysis.

Exploratory Data Analysis (EDA)
During EDA, I explore the dataset thoroughly by:

Visualizing the distributions of key numerical features such as Age, SibSp (number of siblings/spouses aboard), Parch (number of parents/children aboard), and Fare.
Analyzing relationships between different variables to identify potential correlations affecting survival chances.
Detecting outliers and understanding data patterns to guide cleaning and feature engineering.
Data Cleaning
Data cleaning is crucial to improve model performance:

Handling missing values through imputation strategies.
Dropping irrelevant columns such as PassengerId, Cabin, Name, and Ticket.
Creating new features or transforming existing ones to better capture underlying patterns that influence survival outcomes.
Model Testing
Multiple machine learning models are evaluated, including Decision Tree, LightGBM, XGBoost, RandomForest, ExtraTrees, and Logistic Regression. The best-performing model achieves an accuracy of approximately 73.8%, demonstrating its effectiveness in predicting passenger survival.

Test Submission
Using the selected model, I predict survival on the test dataset and prepare a submission file. This step helps evaluate how well the model generalizes to unseen data and is essential for competition submissions.

Conclusion
With an accuracy of 73.8%, the developed model demonstrates a strong ability to forecast Titanic passenger survival. This project illustrates the practical application of machine learning techniques on historical data and offers insights into the key factors influencing survival rates during the Titanic disaster.
