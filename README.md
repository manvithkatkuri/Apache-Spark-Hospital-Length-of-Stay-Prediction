# Apache-Spark-Hospital-Length-of-Stay-Prediction


This project is about implementation and analysis for predicting hospital Length of Stay (LOS) using machine learning models. The project aims to assist healthcare institutions in optimizing resource allocation, improving patient care, and managing operational costs effectively.

## Project Overview

Healthcare institutions face challenges in capacity planning and resource optimization. This project focuses on building predictive models for hospital Length of Stay (LOS) to provide actionable insights that can enhance hospital management efficiency.

### Objectives
- Develop predictive models for hospital LOS.
- Identify critical factors influencing LOS.
- Compare the performance of different machine learning approaches.
- Provide recommendations for practical implementation.

## Methodology

### 1. Data Preparation
- Merged multiple datasets containing patient, hospital, and clinical information.
- Performed data cleaning, standardization, and consistency checks.
- Addressed missing values systematically to ensure data completeness.

### 2. Feature Engineering
- Conducted correlation analysis to select relevant features.
- Focused on clinically significant and statistically robust predictors.

### 3. Model Development
Implemented and compared three predictive models:
- **XGBoost** (Best performer: R² = 0.689, MAE = 0.938, RMSE = 1.465)
- **Random Forest** (R² = 0.394, MAE = 1.123, RMSE = 2.314)
- **Linear Regression** (R² = 0.639, MAE = 1.108, RMSE = 1.785)

### 4. Results and Visualizations
- Analyzed LOS and mortality rate trends across demographic factors (age, gender, race).
- Visualized regional differences in hospital LOS and mortality rates.

## Key Insights

- **Best Model:** XGBoost demonstrated the highest predictive accuracy and robustness, making it the recommended model for deployment.
- **Business Implications:** Predicting LOS allows hospitals to efficiently allocate resources, manage costs, and enhance operational planning.
- **Future Improvements:**
  - Integrating advanced SparkML pipelines for streamlined processing.
  - Implementing hyperparameter tuning using CrossValidator and ParamGridBuilder.

## Technologies Used
- **Programming Languages:** Python
- **Libraries/Frameworks:** PySpark, XGBoost, Matplotlib
- **Tools:** Jupyter Notebook
- **Data Handling:** SparkML, RegressionEvaluator


