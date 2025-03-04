# 🚗 Car Price Prediction

## 📌 Overview
This project aims to develop a **machine learning model** to predict the **selling price of used cars** based on historical data. It involves **data analysis, feature engineering, visualization, and model training** to provide an accurate estimation of car prices.

## 🎯 Project Goals
- **Data Preprocessing**: Clean and prepare the dataset.
- **Feature Engineering**: Extract meaningful features.
- **Exploratory Data Analysis (EDA)**: Understand variable relationships.
- **Model Development**: Train machine learning models to predict car prices.
- **Performance Evaluation**: Assess model accuracy using evaluation metrics.

## 📊 Dataset
- The dataset consists of **301 records** and **9 columns**.
- The data is stored in `car data.csv`.
- Features include car attributes like **Year, Present Price, Kilometers Driven, Fuel Type, Seller Type, Transmission, and Ownership History**.

## 🔍 Data Preprocessing & Feature Engineering
1. **Data Cleaning**
   - Removed unnecessary columns (`Car_Name`).
   - Created a new column `Age_of_Car` (calculated as `2021 - Year`).
2. **Encoding Categorical Variables**
   - Converted categorical columns (`Fuel_Type`, `Seller_Type`, `Transmission`) into numerical form using **one-hot encoding**.
3. **EDA (Exploratory Data Analysis)**
   - Visualized data distributions with bar charts and count plots.
   - Analyzed feature correlations using a heatmap.

## 🏗️ Model Development (Upcoming)
- Implement multiple ML models like **Linear Regression, Decision Tree, and Random Forest**.
- Optimize model performance through **Hyperparameter tuning**.
- Evaluate models using **R² score, RMSE, and MAE**.

## 🚀 Future Enhancements
- Deploy the model as a **web application using Flask/Streamlit**.
- Integrate more features to improve prediction accuracy.

## 🛠️ Tech Stack
- **Python** 🐍
- **Pandas & NumPy** (Data Analysis)
- **Matplotlib & Seaborn** (Visualization)
- **Scikit-learn** (Machine Learning)

## 📂 Project Structure
```
📁 Car-Price-Prediction
│-- 📄 README.md  # Project Documentation
│-- 📄 car data.csv  # Dataset
│-- 📄 car_price_prediction.ipynb  # Jupyter Notebook with Code
```

## 📜 License
This project is open-source and available under the **MIT License**.

---
🚀 **Happy Coding!**
