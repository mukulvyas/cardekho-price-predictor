# 🚗 Cardekho Price Predictor

A machine learning regression project to predict the selling price of used cars based on key features like fuel type, transmission, kilometers driven, and more. The model helps sellers estimate fair car values based on current market trends in India.

---

## 🚀 Objective

To develop a predictive model that can estimate the price of a used car and assist sellers in setting competitive and fair prices based on real-world data scraped from the Cardekho.com platform.

---

## 🗃️ Dataset

- **Source**: Web scraping from [Cardekho.com](https://www.cardekho.com/)
- **Rows**: 15,411  
- **Columns**: 13  
- **Features Include**:
  - Car name
  - Year
  - Present Price
  - Kms Driven
  - Fuel Type
  - Seller Type
  - Transmission
  - Owner
  - Selling Price (Target variable)

---

## 🧼 Data Processing

- Removed duplicates and handled missing values
- Converted text columns to numerical values using encoding
- Feature scaling and selection
- Train-Test split for model training and evaluation

---

## 📊 Exploratory Data Analysis

- Distribution of car prices, years, and kms driven
- Visualizations comparing price with fuel type, transmission, etc.
- Feature importance analysis

---

## 🤖 Models Evaluated

- Linear Regression
- Ridge & Lasso Regression
- K-Nearest Neighbors
- Decision Tree
- **Random Forest (with and without hyperparameter tuning)**

---

## 🏁 Final Results (Best Model: Random Forest Regressor)

- **R² Score on Test Set**: **94.54%**
- **Mean Absolute Error (MAE)**: ₹98,123
- **Root Mean Squared Error (RMSE)**: ₹202,735

This model performed best among all evaluated regressors and showed strong generalization after hyperparameter tuning.

---

## 🔧 Tech Stack

- Python
- Pandas, NumPy
- Scikit-Learn
- Seaborn, Matplotlib

---

## 📂 File Structure

```bash
📦cardekho-price-predictor
 ┣ 📜cardekho_imputated.csv
 ┣ 📜cardekho_price_predictor.ipynb
 ┣ 📜README.md

