# 🏡 House Price Prediction using Linear Regression

This project uses a Linear Regression model to predict house prices based on features from the [Kaggle House Prices dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data).

# 📁 Dataset
Before running the notebook, make sure to upload `train.csv` (from the Kaggle dataset).  You will be prompted to upload the file during execution if using VS CODE.

# 🚀 Workflow

1. **Import Libraries**
2. **Upload & Load Dataset**
3. **Data Preprocessing**:  Select important features and Drop missing values
4. **Train/Test Split**
5. **Model Training**
   - Using `LinearRegression` from scikit-learn
6. **Evaluation**:  Mean Squared Error (MSE) and  R² Score
7. **Custom Prediction**
   - Predict price for a house with 2000 sqft, 3 bedrooms, and 2 bathrooms
8. **Visualization**
   - Scatter plot of Actual vs Predicted prices

# 📊 Model Performance
The model outputs the following performance metrics:
- **Mean Squared Error (MSE)**
- **R² Score**: Coefficient of determination

These metrics help understand how well the linear model fits the data.
