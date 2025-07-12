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
- Train-test split for model training and evaluation

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
- Random Forest
- AdaBoost
- Gradient Boosting
- XGBoost

---

## 🏁 Final Results

| Model               | R² Score | MAE     | RMSE     |
|---------------------|----------|---------|----------|
| Random Forest       | 94.36%   | ₹99,135 | ₹206,047 |
| K-Nearest Neighbors | 90.75%   | ₹117,496| ₹263,888 |
| AdaBoost            | 65.14%   | ₹401,950| ₹512,298 |
| Gradient Boosting   | 93.94%   | ₹97,966 | ₹213,579 |
| XGBoost             | 85.50%   | ₹103,494| ₹330,411 |

**Best Model: Random Forest**, showing strong overall generalization with a high R² score and low error.

---

## 🔧 Tech Stack

- Python
- Pandas, NumPy
- Scikit-Learn
- Seaborn, Matplotlib
- XGBoost

---

## 📂 File Structure

```bash
📦cardekho-price-predictor
 ┣ 📜cardekho_price_predictor.ipynb
 ┣ 📜README.md
 ┗ 📜cardekho_imputated.csv
```

---

## 💡 Future Improvements

- Deploy as a web app using Streamlit/Flask
- Integrate live car listings from Cardekho
- Automate feature engineering and tuning pipeline

---
