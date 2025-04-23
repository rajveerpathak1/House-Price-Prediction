# 🏠 House Price Prediction Using ML

This project predicts house prices based on a variety of features like square footage, location, number of rooms, and more. The goal is to build regression models to evaluate how well we can estimate housing prices using machine learning.

## 📊 Dataset
- **Source:** Public housing dataset (21 columns, 21k+ rows)
- **Features:** bedrooms, bathrooms, sqft_living, sqft_lot, floors, waterfront, view, condition, grade, age, renovation status, and location (lat/long)

## 🔧 Workflow

1. **Data Cleaning**
   - Removed redundant columns (`id`, `date`)
   - Converted float to int where necessary (`bathrooms`, `floors`)
   - Converted `yr_built` to `age` and `yr_renovated` to binary

2. **Feature Engineering**
   - Normalized area-based features using min-max scaling
   - Created `price_range` bins for visual analysis

3. **Exploratory Data Analysis**
   - Correlation matrix
   - Scatter plots, box plots, and bar plots to visualize key trends
   - Interactive map plotted using Folium

4. **Modeling**
   - **Linear Regression with Polynomial Features** (R²: ~0.82)
   - **Ridge Regression** (R²: ~0.71)
   - **Random Forest Regression** (R²: ~0.88, best performer ✅)

5. **Evaluation**
   - R², MAE, MSE, RMSE
   - Actual vs Predicted distribution plots
   - Accuracy comparison across models

## 📌 Key Insight
> Location, square footage, and grade are the most influential features in determining house prices.

## 🔮 Future Improvements
- Use geospatial clustering for more accurate location-based pricing
- Try advanced models like XGBoost, LightGBM

## 💻 Tech Stack
- Python, Pandas, Scikit-learn, Seaborn, Matplotlib, Folium

---



## 📬 Contact
**Rajveer Pathak**  
📧 [tarupa123@gmail.com](mailto:tarupa123@gmail.com)  
🌐 [LinkedIn](https://www.linkedin.com/in/rajveerpathak/) | [GitHub](https://github.com/rajveerpathak1)
