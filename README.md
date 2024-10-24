# Portfolio of Healthcare Models & Dashboard

## Introduction
This repository features three machine learning models and two websites focused on healthcare analytics, predictions, and visualization. These models aim to address anomaly detection, billing prediction, and sales forecasting. Additionally, a **Power BI** dashboard and a billing prediction website provide valuable tools for stakeholders and patients.
![WhatsApp Image 2024-10-24 at 11 20 51_fea954b3](https://github.com/user-attachments/assets/aa9e69cf-661d-43ba-bf37-9232998a6555)


## Project Overview
### 1. **Anomaly Detection with Isolation Forest**
In this project, the Isolation Forest algorithm was employed to detect anomalies in hospital billing amounts, providing hospitals with a mechanism to identify unusual billing patterns.

### Key Steps:
- **Feature Selection**: Numeric features were selected, excluding non-relevant columns like names and dates.
- **Data Preprocessing**: The data was split into training and testing sets.
- **Anomaly Detection**: Trained the Isolation Forest algorithm to classify data as anomalous (-1) or normal (1).
- **Visualization**: Visualized the results, highlighting outliers in billing amounts that may indicate errors or fraud.

### Outcome:
- Identified significant billing anomalies for further investigation, improving financial oversight in hospital management.

### 2. **Hospital Billing Prediction & Future Sales Forecasting**
This model predicts billing amounts for hospitals and provides future sales forecasts for the top 10 hospitals.

### Key Steps:
- **Data Preparation**: 
    - Processed missing values and prepared both categorical and numeric data.
    - Split the data into features and the target variable (`Billing Amount`).
- **Model Building**: Built a Random Forest Regressor model to predict billing amounts.
- **Model Evaluation**: Achieved an MAE of 12,235.62, an MSE of over 205 million, and an accuracy of 52%.
- **Future Sales Prediction**: Linear regression was used to forecast hospital sales for the next 1, 2, and 5 years.

### Outcome:
- Provided valuable predictions for hospital billing amounts and projected future sales, helping hospitals with revenue planning and budgeting.

### 3. **Billing Amount and Admission Days Prediction**
This project focused on predicting both billing amounts and hospital admission days, providing deeper insight into hospital performance and cost-efficiency.

### Key Steps:
- **Data Preprocessing**: Managed missing values and encoded categorical features for modeling.
- **Feature Selection**: Chose relevant features like age, medical condition, etc., with billing amount as the target variable.
- **Model Training**: Trained Random Forest and Gradient Boosting Regressor models. Random Forest performed best, achieving an R² score of 0.91 with 90.68% accuracy.
- **Analysis**: Predicted average billing and identified hospitals with the shortest admission periods.

### Outcome:
- Delivered detailed insights on cost-efficiency and performance, helping to identify hospitals with the lowest costs and shortest stays.

## Websites and Power BI Dashboard

### 1. **Power BI Dashboard for Stakeholders**
A **Power BI** dashboard was created to visualize data insights, aimed at helping stakeholders make data-driven decisions regarding hospital performance and financial trends.

### Key Features:
- **Sales Performance Visualization**: Showcased trends and patterns in hospital billing over time.
- **Market Trend Analysis**: Identified shifts in healthcare market demands and pricing.
- **Predictive Analytics**: Visualized future sales projections and trends.
- **Anomaly Detection**: Highlighted billing anomalies for further scrutiny.

This interactive dashboard offers stakeholders an accessible platform for understanding critical business insights through intuitive visuals.

### 2. **Patient Billing Prediction Website**
The second website caters to patients, allowing them to input personal and medical details to predict their hospital billing amounts.

### Features:
- **Billing Prediction Tool**: Provides an estimated billing amount based on user inputs using machine learning models.
- **User-Friendly Design**: Offers an intuitive interface for patients of all backgrounds to easily access.
- **Secure Data Handling**: Ensures privacy and confidentiality while delivering accurate billing predictions.

This tool helps patients better understand and prepare for their healthcare costs.

## Conclusion
This portfolio presents a range of data science and web development projects aimed at enhancing healthcare efficiency. From anomaly detection to future billing predictions, these models and tools provide hospitals, stakeholders, and patients with actionable insights. The **Power BI** dashboard offers an engaging way for stakeholders to analyze trends, while the billing prediction website empowers patients with financial transparency. Together, these projects support informed decision-making and efficient resource management within the healthcare sector.
