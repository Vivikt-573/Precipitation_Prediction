## 🌧️ Precipitation_Prediction (Popular Machine Learning Models)
Welcome to the Rain Prediction Project! 
This project aims to enhance rain prediction accuracy. It is essential to understand and improve decision-making based on weather conditions and make precipitation forecasting more reliable.

- Kernel - GitHub - Precipidation Prediction

## ℹ️ Introduction
![26408](https://github.com/Vivikt-573/Precipitation_Prediction/assets/148704966/9f693904-9286-422f-94c8-1da725277fa4)
Image Credits - https://www.freepik.com/author/brgfx - brgfx
- In this endeavor,a dedicated effort to harness the power of data and machine learning to enhance our ability to forecast rain. Rain prediction is not just a matter of convenience but a crucial aspect of various sectors, impacting agriculture, water resource management, and disaster preparedness. 

### 💾 Dataset
- The Dataset is used from Kaggle - Rain in Australia
- To Download/Use - [https://www.kaggle.com/datasets/harlfoxem/housesalesprediction/data](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)

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
![image](https://github.com/Vivikt-573/Precipitation_Prediction/assets/148704966/12d43bf1-9545-4137-b178-84de31b9ee7b)


## 🎯 Aim

The primary aim of this project is to create a robust machine learning model that can forecast whether it will rain tomorrow based on a set of relevant weather features. By achieving this, we aim to provide a valuable tool for improving rain prediction accuracy and aiding in decision-making processes dependent on weather conditions.


## 📌 Objective

- To collect and preprocess historical weather data containing features like temperature, wind speed, humidity, and rainfall.
- To design and train a machine learning model capable of accurately predicting rain for the following day.
- To evaluate the model's performance using appropriate metrics such as accuracy, precision, recall, and the area under the ROC curve (AUC-ROC).
- To provide insights into the significance of different weather parameters in rain prediction.
- To offer recommendations for further improvements in precipitation forecasting.


## 🧑‍🔬 Scope and Methodology

- This project focuses on developing a predictive model for rain prediction with the aim of achieving accurate and reliable results.
- The scope encompasses data collection, preprocessing, feature selection, model development, and performance evaluation.
- The model's applicability extends to various regions and locations, making it a valuable tool for meteorologists, agricultural experts, and other stakeholders reliant on precipitation forecasts.


## ✔️📊 Results and Discussion

**Accuracy:**

Random Forest has the highest accuracy on the test set (85.02%), followed closely by XG Boost (85.02%).
Decision Tree and Gradient Boost have similar test accuracies, with Decision Tree at 83.27% and Gradient Boost at 84.60%.
AdaBoost has the lowest test accuracy at 84.10%.
Best: Random Forest and XG Boost (for accuracy).

**AUC-ROC Score:**

Gradient Boost and XG Boost have the highest AUC-ROC scores (0.73), indicating good discrimination between classes.
Random Forest and Decision Tree have AUC-ROC scores of 0.72, suggesting a slightly lower ability to discriminate.
AdaBoost has the lowest AUC-ROC score at 0.71.
Best: Gradient Boost and XG Boost (for AUC-ROC score).

**Precision:**

Random Forest has the highest precision for class 0 (no rain) at 0.86, indicating few false positives.
Gradient Boost and XG Boost have the second-highest precision for class 0 at 0.87.
AdaBoost and Decision Tree also have relatively high precision for class 0.
Precision for class 1 (rain) varies, with XG Boost having the highest at 0.74.
Best: Random Forest (for precision in class 0), XG Boost (for precision in class 1).

**Recall:**

Random Forest has the highest recall for class 0 (no rain) at 0.95, indicating a good ability to capture actual no-rain instances.
XG Boost and Gradient Boost have the second-highest recall for class 0 at 0.94 and 0.95, respectively.
All models exhibit varying levels of recall for class 1 (rain), with XG Boost and Gradient Boost having the highest values at 0.51.
Best: Random Forest (for recall in class 0), XG Boost and Gradient Boost (for recall in class 1).

**F1-Score:**

The F1-scores are highest for class 0 in Random Forest (0.91) and XG Boost (0.91).
For class 1, XG Boost has the highest F1-score at 0.61.
Decision Tree has the lowest F1-scores for both classes, indicating a balance between precision and recall.
Best: Random Forest (for F1-score in class 0), XG Boost (for F1-score in class 1).

**Computational Time (Wall Time):**

Decision Tree is the fastest to train and test (55.2 seconds), followed by AdaBoost (8 minutes and 8 seconds).
Random Forest, XG Boost, and Gradient Boost are computationally intensive, with the longest training and testing times:
Random Forest (8 minutes and 3 seconds)
XG Boost (6 minutes and 37 seconds)
Gradient Boost (14 minutes and 41 seconds).

**Final Summary**

If prioritize accuracy, Random Forest and XG Boost are the top performers.
If prioritize AUC-ROC score, Gradient Boost and XG Boost are strong choices.
For precision and recall in class 0, Random Forest and XG Boost stand out.
For precision in class 1, XG Boost performs well.
For recall in class 1, XG Boost and Gradient Boost are competitive.
If there is need to balance computational efficiency and performance, Decision Tree is the fastest, but Random Forest and XG Boost are also viable options.
**In this context, XG Boost emerges as the leading choice, excelling in performance.**

