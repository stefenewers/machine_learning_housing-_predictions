# 🏡 California Housing Price Prediction

🧠 Beginner-friendly machine learning project that predicts California housing prices using linear regression, data cleaning, and exploratory analysis with Python.

This project uses a real-world dataset from Kaggle to explore how features like income, location, and number of rooms affect home values across California. Inspired by [NeuralNine’s YouTube tutorial](https://www.youtube.com/watch?v=Wqmtf9SA_kk), this was my first hands-on ML build from data prep to model evaluation.

🔗 **Dataset**: [Kaggle - California Housing Prices](https://www.kaggle.com/datasets/camnugent/california-housing-prices)  
🎥 **Tutorial Guide**: [NeuralNine YouTube Walkthrough](https://www.youtube.com/watch?v=Wqmtf9SA_kk)

---

## 📁 Project Structure


---

## 🚀 Features & Concepts Covered

- Data cleaning with `pandas`
- Exploratory Data Analysis (EDA)
- Correlation heatmaps with `seaborn`
- One-hot encoding for categorical values
- Train-test split using `scikit-learn`
- Linear Regression model building
- Evaluation using Mean Absolute Error (MAE)

---

## 📊 Dataset Overview

Each row represents a block group in California and includes:

- `longitude`, `latitude`
- `housing_median_age`
- `total_rooms`, `total_bedrooms`
- `population`, `households`
- `median_income`
- `ocean_proximity` *(categorical)*
- `median_house_value` *(target)*

---

## 📈 Key Insights

- **Median income** was the most predictive feature of housing prices.
- Even with a basic linear regression model, the predictions were surprisingly reasonable.
- Areas with high price variance (outliers) reduced model accuracy—room for future improvements!

---

## 💡 Why This Project Was Important

This was my first end-to-end machine learning project. I learned:
- How to prepare and clean a real-world dataset
- How features affect predictions
- How simple models can still be powerful
- The importance of visualization in spotting relationships

---

## 📦 Setup & Requirements

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
