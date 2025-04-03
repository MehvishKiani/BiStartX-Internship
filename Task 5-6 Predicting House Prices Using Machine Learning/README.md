**Predicting House Prices Using Machine Learning**
Week 5-6 (April 1 - April 14) | BiStartX Internship

📌** Project Overview**
This project focuses on predicting house prices using Machine Learning (ML) techniques. The dataset contains various features such as area, number of bedrooms, bathrooms, stories, parking, and additional amenities like air conditioning, guestroom, basement, etc.

The model applies data preprocessing, exploratory data analysis (EDA), feature engineering, and model training using XGBoost to make accurate price predictions.

📊 **Dataset Information**
Target Variable: price (House price)

**Features:**

Numerical: area, bedrooms, bathrooms, stories, parking

Categorical: mainroad, guestroom, basement, hotwaterheating, airconditioning, prefarea, furnishingstatus

The dataset contains 545 records with no missing values.

🔧 Technologies & Tools Used
Python

Pandas, NumPy (Data Processing)

Matplotlib, Seaborn (Data Visualization)

Scikit-learn (Data Preprocessing & Model Evaluation)

XGBoost (Machine Learning Model)

🚀 **Implementation Steps**
1️⃣ Data Preprocessing
✔ Handling categorical variables using One-Hot Encoding
✔ Normalizing numerical values using StandardScaler

2️⃣ **Exploratory Data Analysis (EDA)**
✔ Checking dataset distribution
✔ Visualizing correlations using heatmaps and pairplots
✔ Understanding feature importance

3️⃣ **Model Training & Evaluation**
✔ Splitting the data into train and test sets
✔ Training an XGBoost Regressor
✔ Evaluating model using MAE, RMSE, and R² score
