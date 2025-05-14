# realestate-price-predictor
This project aims to predict residential house prices in Bengaluru using regression models.



## ✅ Objective
To estimate house prices based on features like square footage, location, BHK, bathrooms, etc.



## ⚙️ Tools Used
- Python, Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn



## 📊 Model Building
- Extracted BHK from 'size' column
- Cleaned `total_sqft`, removed outliers
- Created dummy variables from 'location'
- Tried multiple models: Linear Regression, Gradient Descent, Random Forest



## 🧠 Best Model
- 🎯 **RandomForestRegressor**
- 🛠️ **Tuned with RandomizedSearchCV**
- 📈 **Best R² Score Achieved:** **60%**

---

## 📈 Visualizations
- Price Distribution
- Sqft vs Price Scatter Plot
- Feature Importance



## 📁 Files
- `real_estate_prediction_final.ipynb` – Main notebook
- `README.md` – Project summary



## 📂 Dataset
[📥 Kaggle: Bengaluru House Data](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)
