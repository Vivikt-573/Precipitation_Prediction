## 🏠💵 Precipitation_Prediction (Popular Machine Learning Models)
With this comprehensive portfolio, I cordially invite you to explore the in-depth study conducted on the dynamics of house prices in King County, specifically in the vibrant city of Seattle.
- Kernel - GitHub - House Price Prediction

## ℹ️ Introduction
![44771](https://github.com/Vivikt-573/House-Price-Prediction---Regression-Models/assets/148704966/87e87c0f-aef0-45e7-a527-c3310da0afc0)
Image Credits - https://www.freepik.com/author/brgfx - brgfx
- The project revolves around a comprehensive analysis of house sale prices in King County, encompassing the city of Seattle, with a dataset spanning the period from May 2014 to May 2015. This analysis aims to gain insights into the factors influencing house prices and to develop predictive models for future price forecasts.

### 💾 Dataset
- The Dataset is used from Kaggle - House Sales in King County, USA
- To Download/Use - https://www.kaggle.com/datasets/harlfoxem/housesalesprediction/data

### 📚🛠️ Libraries/Tools
- Python
- Sklearn
- XGboost
- Pandas
- Numpy
- Seaborn
- Matplotlib
- Category Encoders


### 👨🏻‍💻 Workflow
The project follows a systematic methodology, which includes data cleaning, exploratory data analysis, feature engineering, and machine learning modeling etc,To obtain a precise visual representation, please refer to the flowchart provided below. 
![image](https://github.com/Vivikt-573/House-Price-Prediction---Regression-Models/assets/148704966/38f391c1-be3f-4ab0-9bf1-f979521e3bc6)



## 🎯 Aim

The primary aim of this project is to understand and predict house prices in King County. By leveraging various features of the dataset, we seek to uncover patterns and relationships that impact property values. This understanding will enable us to construct predictive models to estimate house prices, which can be invaluable for both buyers and sellers in the real estate market.


## 📌 Objective

- Explore the dataset to gain a thorough understanding of the available features and their relationships with house prices.
- Perform data quality checks, handle missing values, duplicates, and outliers to ensure the dataset's integrity.
- Conduct exploratory data analysis (EDA) to visualize data patterns, correlations, and distributions.
- Provide valuable insights and recommendations for stakeholders in the real estate market.


## 🧑‍🔬 Scope and Methodology

- Engineer relevant features and transform data to prepare it for modeling.
- Evaluate model performance using appropriate metrics and techniques.
- Implement cross-validation and hyper-parameter tuning for improved model accuracy.
- Implement multiple regression models, including Linear, Ridge, and Lasso, to predict house prices.

## ✔️📊 Results and Discussion

**Positive Impact on Price:**
1. Features such as 'sqft_living,' 'grade,' 'sqft_above,' 'sqft_basement,' 'view,' 'waterfront,' 'lat,' and 'sqft_living15' have positive coefficients in all three models.
2. This indicates that an increase in these features tends to result in a higher predicted price for the property.
  
**Negative Impact on Price:**
1. Features like 'bedrooms,' 'yr_built,' 'long,' 'sqft_lot,' 'zipcode,' and 'sqft_lot15' have negative coefficients in all three models.
2. This means that an increase in these features is associated with a lower predicted price for the property.
  
**Comparison of Models:**
1. The magnitude of coefficients may vary between models. For example, 'sqft_living' has the highest positive coefficient in all three models, but the values differ slightly. Lasso regression, due to its feature selection property, sets some coefficients to zero. In this case, it sets zipcode,sqft_basement,' 'sqft_lot,' and 'long' coefficients to zero, indicating that these features are not essential in predicting the price.
  
**Effect of Regularization:**
1. Ridge and Lasso regression introduce regularization to the model. This is reflected in the Ridge and Lasso coefficients, which are slightly smaller than the Linear coefficients for most features.
2. Regularization helps prevent overfitting and can make the model more robust.
  
**Feature Importance:**
1. 'lat' and 'sqft_living' appear to be among the most influential features, with high positive coefficients in all three models.
2. 'sqft_basement' is essentially eliminated in the Lasso model, suggesting it has a limited impact on the price.
3. The 'yr_renovated' feature has relatively small coefficients in all models, indicating it may not be a strong predictor of price.


