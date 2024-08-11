Project Title: Rain Prediction Using Machine Learning

Objective:
Developed a machine learning model to predict whether it will rain tomorrow in Australia using various classification algorithms, achieving a high accuracy rate.

Data Pre-processing:

Imported and cleaned weather data by removing irrelevant columns (e.g., location, date) and columns with excessive missing values.
Eliminated rows with missing data and outliers using Z-score.
Converted categorical variables like RainToday and RainTomorrow to binary form (1 for Yes, 0 for No).
Standardized the dataset using MinMaxScaler for uniform feature scaling.
Feature Selection:

Identified top predictive features using SelectKBest with the chi-squared test, narrowing down to the most relevant ones, including Humidity3pm.
Modeling and Evaluation:

Built and evaluated multiple classifiers including Logistic Regression, Random Forest, Decision Tree, and Support Vector Machine (SVM).
Split data into training and testing sets using an 80-20 ratio.
Achieved the following results:
Logistic Regression: Accuracy ~84%, faster computation time.
Random Forest Classifier: Accuracy ~84%, moderate computation time.
Decision Tree Classifier: Accuracy ~83%, fastest computation time.
Support Vector Machine: Lower accuracy with significantly higher computation time.
Outcome:

The Decision Tree Classifier was selected as the optimal model due to its balance of accuracy and computation efficiency.
Successfully demonstrated the ability to preprocess data, perform feature selection, and build various machine learning models, leading to effective predictions with real-world data.
Technologies Used:

- Languages: Python
- Libraries: Pandas, NumPy, Scikit-learn, Scipy
- Techniques: Data Cleaning, Feature Selection, Model Evaluation, Cross-Validation
