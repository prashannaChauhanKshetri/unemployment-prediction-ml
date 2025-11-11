# Unemployment Rate Prediction using Machine Learning

## 🎯 Project Overview
Regression analysis predicting unemployment rates based on socio-economic indicators using multiple ML models.

## 📊 Key Results
- **Best Model:** Random Forest Regressor
- **Performance:** R² = 0.95, MSE = 0.01
- **Dataset:** South Asian socio-economic data (7 features)
- **Top Features:** Police Trust, School Quality, House Cost

## 🛠️ Technologies Used
- Python 3.x
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- StandardScaler, LabelEncoder

## 🔍 Models Implemented
1. Linear Regression (from scratch using Gradient Descent)
2. Linear Regression (Scikit-learn)
3. Ridge Regression
4. Lasso Regression
5. Decision Tree Regressor
6. Random Forest Regressor (Best: R²=0.95)

## 📈 Methodology
1. **Data Preprocessing**
   - Handled missing values
   - Feature scaling with StandardScaler
   - Label encoding for categorical variables

2. **Exploratory Data Analysis**
   - Correlation heatmaps
   - Outlier detection with boxplots
   - Feature distribution analysis

3. **Model Training & Optimization**
   - Hyperparameter tuning with GridSearchCV
   - Recursive Feature Elimination (RFE)
   - Cross-validation for model evaluation

4. **Evaluation Metrics**
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
   - R-squared (R²)
   - Cross-validation scores

## 💡 Key Insights
- Random Forest outperformed linear models by significant margin
- Public trust in institutions ('policetrust') had highest impact on unemployment
- Decision Tree showed overfitting (R²=0.99 on training) - validation necessary

## 📁 Project Structure
