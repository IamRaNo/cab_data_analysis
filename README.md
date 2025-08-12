# 🚖 Cab Data Analysis, Visualization & Dynamic Price Estimation

This project analyzes cab trip data from multiple sources, explores key trends, and builds a **dynamic fare prediction model** using machine learning.  
It includes **data cleaning, exploratory data analysis (EDA), feature engineering, visualization, and model building** for fare estimation.

---

## 📌 Project Overview
The main goals of this project were:
- **Data Preparation:** Merge and clean multiple datasets (transactions, customers, taxis, cities).
- **EDA & Insights:** Identify the most influential factors affecting cab fares.
- **Visualization:** Explore customer demographics, trip patterns, company market share, and fare distribution.
- **Model Building:** Develop a machine learning model to predict cab fares dynamically.
- **Hyperparameter Tuning:** Use GridSearchCV with XGBoost to optimize model performance.

---

## 📂 Dataset Information
The project works with:
- **Transaction Data:** Trip IDs, customer IDs, distances, costs, fares, and payment details.
- **Customer Data:** Age, gender, income, city, and state information.
- **Taxi Data:** Company names (Yellow, Pink), transaction links.
- **City Data:** City names and population sizes.

---

## 🔍 Key Analysis Highlights
- **Top User Cities:** New York, San Francisco, and Chicago dominate in absolute users, while **San Francisco, Boston, and Washington DC** have the highest engagement rates relative to population.
- **Company Market Share:** Yellow taxis hold ~76% market share but show more extreme pricing than Pink.
- **Pricing Patterns:**  
  - Higher fares at the start of the year compared to the end.  
  - Weekends see the highest average fares.  
  - Longer distances cause greater price variability.
- **Correlations:** Distance and cost show strong positive correlation with fare amount.

---

## ⚙️ Machine Learning Model
- **Algorithm:** XGBoost Regression
- **Pipeline:** ColumnTransformer for scaling & encoding + XGBoost model
- **Hyperparameter Tuning:** GridSearchCV to find best parameters
- **Target:** Fare price prediction

---

## 📊 Technologies Used
- **Languages:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost
- **Tools:** Jupyter Notebook

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cab-fare-analysis.git
   cd cab-fare-analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook and run:
   ```bash
   jupyter notebook cab_data_analysis.ipynb
   ```

---

## 📈 Results
The final model is capable of predicting cab fares based on trip and customer details, helping companies optimize pricing strategies dynamically.

---
