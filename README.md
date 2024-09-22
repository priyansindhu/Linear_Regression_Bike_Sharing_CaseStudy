# Bike_Sharing_Linear_Regression
# Problem Statement

BoomBikes, a US-based bike-sharing provider, has faced revenue declines due to the COVID-19 pandemic and seeks to understand the factors driving demand for shared bikes in the American market. The company aims to predict bike demand post-pandemic using available data on daily bike usage and other factors, enabling them to adjust their business strategy accordingly. The objective is to build a model that identifies significant predictors of demand and helps the company meet customer needs while standing out in a competitive market

# Steps Involved

- **Data Standardization and Cleaning:** Handled missing values, Dropped redundant columns and Mapped categorical columns to meaningful values based on the data dictionary for easier understanding and visualization
- **EDA with Univariate, Bivariate, and Multivariate Analysis:** Analyzed distributions, relationships, and interactions between features (e.g., cnt vs. temperature, holiday effect) using visualizations.
- **Data Preparation for Linear Regression:** Train-Test Split was done and feature rescaling was performed.
- **Data Modeling:** Built a linear regression model to predict bike demand based on the independent variables and handled multicollinearity for regression modeling.
- **Validating Assumptions:** Checked linear regression assumptions, including linearity, normality, homoscedasticity, and multicollinearity.
- **Model Evaluation:** Evaluated model performance using metrics such as R², adjusted R², and RMSE to assess predictive accuracy.
- **Making Predictions:** Used the finalized model to predict bike demand, providing insights into future demand dynamics and business strategy adjustments.

# Key Insights

Successfully achieved a **R² score of 0.82**, indicating a strong correlation between the predicted and actual bike rental demand, thus providing valuable insights for strategic planning and enhancing customer satisfaction;  Key Factors affecting rental demand are **temperature, year and windspeed**
