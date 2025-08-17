## 🛒 Black Friday Sales Prediction
# 📌 Project Overview

The goal of this project is to build a predictive model to forecast purchase amounts during Black Friday sales based on customer demographics (e.g., age, gender) and product information.

By analyzing user demographics, product categories, and past purchase amounts, the model identifies key factors that influence sales and provides insights for businesses to:

Optimize inventory management

Target marketing campaigns effectively

Maximize revenue during one of the year’s biggest shopping events

**Success Criteria:** Model accuracy measured using Mean Absolute Error (MAE) and R-Squared, ensuring reliable predictions and actionable insights into customer purchasing behavior.

# 🎯 Objectives

Forecast customer purchase amounts during Black Friday sales

Identify key factors influencing buying behavior

Provide insights for better inventory planning and promotions

Improve customer satisfaction through availability of high-demand products

# 📂 Dataset

**The dataset contains:**

**User Demographics:** Age, Gender, City, Occupation, etc.

**Product Information:** Product categories, product ID, etc.

**Purchase History:** Previous purchase amounts

# ⚙️ Approach
**a. Data Preprocessing**

**Cleaning:** Handle missing values, correct data types, and remove/replace invalid entries

**Feature Engineering:** Create new features (e.g., age groups, category grouping)

**Scaling & Encoding:** Standardize numerical features and encode categorical variables

**b. Model Selection**

**Test and compare multiple regression models:**

Linear Regression

Decision Trees

Random Forest Regressor

Gradient Boosting Regressor

**c. Model Training & Evaluation**

Train-Test Split: 70-30 or 80-20 split

**Evaluation Metrics:**

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R-Squared (R²)

**d. Prediction & Analysis**

Use the best-performing model to predict purchase amounts on the test set

Perform feature importance analysis to understand factors influencing purchases

# 📊 Expected Outcomes

Accurate purchase predictions with minimized error

Identification of key demographic and product-based drivers of sales

Actionable insights for inventory planning, promotions, and customer targeting

# 🛠️ Tech Stack

**Programming Language:** Python

**Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

**Environment:** Jupyter Notebook / Google Colab

# 🚀 Business Impact

Improved inventory optimization by forecasting demand

Better marketing targeting through customer insights

Increased profitability by aligning promotions with predicted customer behavior

Enhanced customer satisfaction with better product availability

# 📈 Future Work

Implement deep learning models (Neural Networks) for better accuracy

Explore time-series forecasting for purchase trends

Build a real-time dashboard for sales prediction visualization
