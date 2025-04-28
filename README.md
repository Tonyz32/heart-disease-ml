# ❤️ heart-disease-ml
A machine learning project to predict heart disease risk using patient health indicators. This project demonstrates data cleaning, exploratory data analysis (EDA), feature engineering, and model development. It’s part of my portfolio to showcase my ability to apply data science methods to real-world public health problems.

## Project Overview
Cardiovascular disease remains one of the leading causes of death globally. The ability to predict heart disease early using clinical indicators has the potential to save lives. This project uses a public dataset to build a machine learning pipeline aimed at identifying high-risk individuals based on features like cholesterol, blood pressure, and chest pain type.

## 📊 Dataset
This project uses the [Heart Failure Prediction dataset from Kaggle](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction).  
It contains 918 observations and 12 health-related features, including:

- Age
- Sex
- Chest Pain Type
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Max Heart Rate
- ST Depression
- Exercise-induced Angina

## Project Goals
- Clean and preprocess the dataset
- Visualize feature relationships using correlation heatmaps and plots
- Identify patterns and predictors of heart disease
- Build machine learning models to predict heart disease status
- Evaluate model performance using relevant classification metrics
- Explain and interpret model decisions to support transparency in health risk prediction

## 📈 Results Summary
Three machine learning models were trained and evaluated to predict heart disease risk: Random Forest, XGBoost, and Logistic Regression.  
All models demonstrated strong predictive performance, with **Random Forest** achieving the highest overall F1 score (88.9%) and ROC AUC (92.4%).  
**Logistic Regression** achieved the best recall (93.1%), which is particularly important in healthcare settings to minimize missed cases.  
Overall, the models showed balanced precision, recall, and AUC metrics, highlighting the project’s success in developing accurate and reliable heart disease risk predictions.

| Model                  | Accuracy | Precision | Recall  | F1 Score | ROC AUC  |
|-------------------------|----------|-----------|---------|----------|----------|
| **Random Forest**       | 87.5%    | 87.6%     | 90.2%   | 88.9%    | 92.4%    |
| **XGBoost**             | 87.0%    | 89.8%     | 86.3%   | 88.0%    | 92.3%    |
| **Logistic Regression** | 87.5%    | 85.6%     | 93.1%   | 89.2%    | 89.6%    |

## 📊 Data Visualizations
Here’s a heatmap showing the correlation between different features in the dataset.

![Correlation Heatmap](images/correlation_heatmap.png)

This plot visualizes the relationships between variables and helps in feature selection for machine learning models.



## Skills Demonstrated
- Data cleaning and visualization with Pandas, Matplotlib, and Seaborn  
- Statistical and epidemiological thinking  
- Exploratory data analysis and feature correlation  
- Machine learning fundamentals  
- Git/GitHub workflow and documentation  

## Author
**Antonio Zapata.**  
data analyst & aspiring data scientist  
GitHub: [Tonyz32](https://github.com/Tonyz32)
