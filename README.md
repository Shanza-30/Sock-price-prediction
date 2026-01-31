# 📈 Stock Price Prediction Using Machine Learning

This project focuses on **short-term stock price prediction** using historical stock market data.  
A Machine Learning regression model is trained to predict the **next day's closing price** based on features such as **Open, High, Low, and Volume**.


## 🎯 Objective
To predict the **next day’s closing stock price** using historical time-series data and regression techniques.


## 📊 Dataset
- **Source:** Kaggle – Major Tech Stocks Time Series (2019–2024)
- **Stock Used:** Apple (AAPL)
- **Features:**
  - Open
  - High
  - Low
  - Volume
- **Target Variable:**
  - Next Day Close Price


## 🛠️ Technologies & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn


## 🧠 Machine Learning Model
- **Algorithm:** Linear Regression
- **Approach:**  
  - Time-series friendly train-test split (no shuffling)
  - Target created using next day closing price (`shift(-1)`)


## 🔄 Project Workflow
1. Load historical stock data  
2. Data preprocessing and sorting by date  
3. Feature selection (Open, High, Low, Volume)  
4. Target creation (Next Day Close)  
5. Train-test split  
6. Model training using Linear Regression  
7. Prediction and evaluation  
8. Visualization of Actual vs Predicted prices  


## 📈 Visualization
The project includes a plot comparing:
- **Actual closing prices**
- **Predicted closing prices**

This helps visually evaluate model performance.


## 📏 Model Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score


## 🔮 Sample Prediction
The trained model can also predict the **next day's closing price** using the latest available stock data.


## 🚀 Future Improvements
- Implement Random Forest Regressor
- Add technical indicators (Moving Averages)
- Extend to multiple stocks
- Deploy as a web app using Flask or Streamlit
