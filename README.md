# Zeronet
Project Title:
Optimizing Carbon Capture Strategies Through Advanced Analytics Using Machine Learning

1. Project Goal:
The aim of the project is to optimize carbon capture strategies by accurately predicting CO₂ emissions. This is done by comparing the performance of two machine learning models, Linear Regression (LR) and Support Vector Regression (SVR), using evaluation metrics to determine which model better forecasts CO₂ emissions. The objective is to guide decision-making for effective carbon capture and storage (CCS) strategies.

2. Objectives:
Predict CO₂ emissions using machine learning models.
Compare Linear Regression and Support Vector Regression based on performance metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R² score.
Provide recommendations for the best model to use in optimizing CCS strategies based on prediction accuracy.
3. Data Collection:
Dataset Used: The "EDA - CO2 Emissions Dataset" from Kaggle, containing data on global CO₂ emissions across different time periods and regions.
Scope: The analysis focuses on predicting CO₂ emissions specifically for Indonesia due to its unique geographic, economic, and environmental factors.
Data Variables:
Entity: Name of country/region.
Year: Year of CO₂ emissions.
Emissions: CO₂ emissions recorded for each year.
4. Data Cleaning:
The dataset was preprocessed to ensure precision and reliability:

Handling Missing Data: Missing values, particularly in the Code column, were identified and either removed or imputed.
Outlier Detection: Outliers were checked, especially in the emission values, to ensure that extreme values did not distort model performance.
Normalization: Data was scaled to ensure consistency and improve the performance of the machine learning models.
5. Analysis & Methodology:
The project used two machine learning models for analysis:

Linear Regression (LR): This model predicts CO₂ emissions by establishing a linear relationship between the emissions and the time-based features.

Support Vector Regression (SVR): This model uses a more flexible and robust approach, capturing complex relationships in the data but sometimes at the cost of interpretability.

Evaluation Metrics:

MSE (Mean Squared Error): Measures the average squared difference between actual and predicted values.
MAE (Mean Absolute Error): Measures the average magnitude of errors in predictions.
R² Score: Indicates how well the model explains the variability in the data.
6. Results:
Linear Regression:
MSE: Lower value, indicating fewer prediction errors.
MAE: Slightly higher than SVR, but still close.
R² Score: Positive, indicating good model fit.
Support Vector Regression:
MSE: Significantly higher than LR, indicating more prediction errors.
MAE: Slightly lower than LR, but overall performance was poorer.
R² Score: Negative, indicating poor model fit.
7. Conclusion:
The analysis found that Linear Regression outperformed Support Vector Regression in predicting CO₂ emissions in Indonesia. Despite SVR being more flexible, its performance was inferior in this context, making Linear Regression the recommended model for future predictions. This result helps optimize Carbon Capture and Storage (CCS) strategies, providing a valuable tool for mitigating climate change.
