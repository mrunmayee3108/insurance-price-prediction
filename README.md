# 🏥 Insurance Cost Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting **medical insurance charges** based on customer demographic and lifestyle information such as age, BMI, smoking status, region, and number of children.

The goal is to build a regression model that can accurately estimate insurance charges and identify the key factors influencing medical expenses.


## 🎯 Objectives

* Perform Exploratory Data Analysis (EDA)
* Identify key factors affecting insurance charges
* Apply feature engineering techniques
* Build and evaluate regression models
* Compare model performances
* Predict insurance costs for new customers


## 📊 Dataset Description

The dataset contains the following features:

| Feature  | Description                              |
| -------- | ---------------------------------------- |
| age      | Age of the policyholder                  |
| sex      | Gender                                   |
| bmi      | Body Mass Index                          |
| children | Number of dependents                     |
| smoker   | Smoking status                           |
| region   | Residential area                         |
| charges  | Medical insurance cost (Target Variable) |


## 🔍 Exploratory Data Analysis (EDA)

Key insights discovered:

* Smoking status has a **strong impact** on insurance charges.
* BMI and age positively correlate with medical expenses.
* Smokers have significantly higher insurance costs.
* Certain regions show moderate variations in charges.

Visualizations used:

* Distribution plots
* Box plots
* Correlation heatmap


## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook


## ⚙️ Machine Learning Workflow

1. Data Cleaning
2. Encoding Categorical Variables
3. Train-Test Split
4. Model Training
5. Model Evaluation

Models Implemented:

* Linear Regression
* Random Forest Regressor

Evaluation Metrics:

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)


## 📈 Model Performance


| Model             | R² Score  | 
| ----------------- | --------  | 
| Linear Regression | 0.8041    | 
| Random Forest     | 0.8407    |



## 🚀 How to Run the Project

1. Clone the repository:

```
git clone https://github.com/mrunmayee3108/insurance-cost-prediction.git
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Run the Jupyter Notebook:

```
jupyter notebook insurance.ipynb
```


## 👩‍💻 Author

Mrunmayee Sachin Potdar


⭐ If you found this project useful, consider giving it a star!
