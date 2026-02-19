# 🏠 House Price Prediction Project

## 📊 Dataset Overview
**Source**: Kaggle  
**Size**: 21,613 rows × 21 columns  
**Key Features**:
id, date, price, bedrooms, bathrooms, sqft_living, sqft_lot, floors,
waterfront, view, condition, grade, sqft_above, sqft_basement,
yr_built, yr_renovated, zipcode, lat, long, sqft_living15, sqft_lot15

## 🔍 Data Preprocessing Pipeline

✅ No null values detected
🗑️ Dropped unnecessary columns
🔄 Applied transformations: cbrt(), log() for skewed data

## 📈 Modeling Journey

### **Phase 1: Baseline Model**
❌ OLS Regression
⚠️ Issue: High correlation between independent features
→ Inaccurate results due to multicollinearity

### **Phase 2: Regularization Techniques**
🎯 Feature Selection Methods:

Lasso Regression

Ridge Regression

ElasticNet

🔧 Hyperparameter Tuning: GridSearchCV
✅ Found optimal parameters for each technique

### **Phase 3: Ensemble Methods**
🚀 Advanced Techniques:

Bagging methods

Boosting methods
🏆 XGBoost Regressor dominated with R² = 87%
## 🏅 Final Results

🥇 XGBoost Regressor: R² = 87%
🥈 Boosting Techniques: Strong performers
🥉 Regularization Models: Baseline improvement
## 🎯 Key Takeaways
- **Correlation handling** was crucial for model stability
- **XGBoost** excelled in capturing complex patterns
- **GridSearchCV + Ensemble methods** = Winning combination

---

**Project successfully transformed raw data into a robust 87% accurate prediction model!** 🎉
