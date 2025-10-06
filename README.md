
# Bank Customer Churn Analysis & Prediction

## Project Overview
This project analyzes bank customer churn patterns and builds predictive models to identify customers at risk of leaving the bank. By understanding churn factors and predicting future churn, banks can implement targeted retention strategies and reduce customer attrition.

## Objectives
- Analyze historical customer data to identify churn patterns and key drivers
- Build machine learning models to predict customer churn probability
- Provide actionable insights for customer retention strategies
- Evaluate model performance and select the best predictor

##  Dataset
The analysis uses bank customer data including:
- **Customer Demographics**: Age, gender, geography
- **Account Information**: Balance, credit score, tenure
- **Product Usage**: Number of products, credit card status, active membership
- **Target Variable**: Churn status (0 = Retained, 1 = Churned)
- <a href="https://github.com/ABHI91827/Bank_Churn_Analysis/blob/main/Churn_Modelling.csv">DATASET</a>

##  Analysis Workflow

### 1. Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Missing value and outlier treatment
- Statistical summary and distribution analysis
- Correlation analysis between features
- Churn rate analysis across different customer segments

### 2. Feature Engineering
- Created new features from existing variables
- Encoded categorical variables
- Scaled numerical features
- label encoding
- Handled class imbalance in the target variable

### 3. Predictive Modeling
Built and evaluated multiple machine learning models:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting (XGBoost/LightGBM)
- Support Vector Machine (SVM)

### 4. Model Evaluation
- Accuracy, Precision, Recall, F1-Score
- Confusion matrix visualization
- Feature importance analysis

## Key Findings
- Identified top factors contributing to customer churn
- Determined customer segments with highest churn risk
- Achieved [%86] prediction accuracy with [RandomForestClassifier]
- Generated actionable retention recommendations

##  Technologies Used
- **Programming Language**: Python
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Machine Learning**: Scikit-learn
- **Development Environment**: Jupyter Notebook / Google Colab

##  Results
- **Best Model**: [RandomForestClassifier] with [86%] accuracy
- <a href="https://app.powerbi.com/groups/me/reports/4db5cbf0-12e0-4915-b532-e1a04b389ddd?experience=power-bi">DASHBOARD</a>
## Bank churn Analysis:
![image alt](https://github.com/ABHI91827/Bank_Churn_Analysis/blob/347f3e503f582ce30ac0d4f0b153f85a458b8cbd/Screenshot%202025-10-06%20190055.png)
## predicted churn Analysis:
![image alt](https://github.com/ABHI91827/Bank_Churn_Analysis/blob/789836c70b2889a1747fad35a409b6e34d1e607e/Screenshot%202025-10-06%20190125.png)



##  Author
[K ABHISHEK]
- LinkedIn: [https://linkedin.com/in/abhishek-k-78020a383]
- GitHub: [https://github.com/ABHI91827]
- Email: [abhishekkarnam18@gmail.com]



*This project demonstrates end-to-end data analytics and data science workflow including EDA, feature engineering, model building, and business insights generation.*
