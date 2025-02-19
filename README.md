# ML Assignment 1: Statistical Measures

## 📌 Project Overview
This project explores the correlation between numerical variables in a real estate dataset using statistical measures and visualization techniques.

## 📊 Dataset Description
The dataset includes the following columns:
- `total_sqft`: Total square feet of the property.
- `bath`: Number of bathrooms.
- `price`: Property price (in lakhs).
- `bhk`: Number of bedrooms, hall, and kitchen.
- `price_per_sqft`: Price per square foot.
- `location`: Categorical variable (not used in numerical correlation).

## 🔍 Exploratory Data Analysis (EDA)
- Checked missing values and removed inconsistencies.
- Converted non-numeric data (like `size`) into structured formats.

## 📈 Correlation Analysis
- Used scatter plots and correlation coefficients to analyze relationships.
- Applied **log transformation** to `price_per_sqft` to handle skewness.
- Explored **log transformations on `price` and `total_sqft`** for better insights.

## 🔬 Findings
- **`total_sqft` vs `price`** showed a **positive but weak correlation** due to outliers.
- After applying **log transformation**, correlation improved.
- **Outliers were identified**, and possible filtering methods were suggested.

## 📌 Next Steps
- Consider removing extreme outliers for better model accuracy.
- Explore additional features like `location` effects on price.

## 🛠️ Tools Used
- **Python (Pandas, NumPy, Matplotlib, Seaborn)**
- **Jupyter Notebook**

---
🔗 *Author: Agishma K P*
