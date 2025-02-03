# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING
COMPANY:CODTECH IT SOLUTIONS

NAME:Anguluri Hima Varshitha

INTERN ID:CT08ILS

DOMAIN:Data Analysis

DURATION:4 weeks

MENTOR:Neela Santhosh Kumar

Description:This project focuses on predicting used car prices using a Linear Regression model. The dataset, `cars.csv`, contains attributes such as brand, body type, mileage, engine volume, engine type, registration status, year, and model. The workflow begins with data loading, where columns like `Price`, `Mileage`, `EngineV`, and `Year` are converted to numeric format, handling non-numeric values by converting them to `NaN`. Missing values are imputed using the mean strategy with **SimpleImputer**, ensuring a complete dataset for analysis. Categorical variables (`Brand`, `Body`, `Engine Type`, `Registration`, and `Model`) are one-hot encoded to transform them into numerical features suitable for the model. The dataset is then split into features (`X`) and the target variable (`y`), followed by a division into training and testing sets using an 80-20 ratio. A Linear Regression model is trained on the data due to its simplicity and interpretability. Model evaluation is conducted using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²). The model achieves an MAE of 7511.42, MSE of 197022468.41, and R² of 0.55, indicating moderate performance. Predictions on new car data are made by preprocessing the input in the same way as the training data to maintain compatibility. The project demonstrates practical applications in the automotive industry, helping buyers estimate fair car prices and enabling sellers to determine appropriate listing prices. Automotive marketplaces can integrate such models for price recommendations, enhancing user experience. Car dealerships and manufacturers can leverage predictive analytics for pricing strategies and inventory management. Additionally, this project provides educational value for data science students, illustrating the full pipeline from data preprocessing to model evaluation and prediction. The workflow can be extended by incorporating advanced models such as Random Forest or Gradient Boosting and additional features like location and fuel type to improve prediction accuracy. The Linear Regression model provides a solid baseline, but further experimentation with sophisticated algorithms and feature engineering can yield better results. Ultimately, this project underscores the importance of data preprocessing, model selection, and evaluation in building effective machine learning solutions, offering valuable insights into predictive analytics.

output:
![Image](https://github.com/user-attachments/assets/13b7174b-b941-4044-a51d-02286b0b486a)
