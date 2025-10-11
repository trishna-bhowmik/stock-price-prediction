📈 Stock Price Prediction

An AI-powered Stock Price Prediction System that estimates future stock values using the rolling average of past data. Built with Python, Pandas, NumPy, Matplotlib, Scikit-learn, Keras, and Streamlit for interactive visualization and deployment.

🚀 Features

📊 Data Analysis & Visualization: Historical stock data analysis using yfinance.
🔮 Prediction Model: Predicts future prices using rolling average and LSTM/Keras models.
🧠 Machine Learning Integration: Incorporates regression-based models for trend forecasting.
💻 Interactive Dashboard: Developed with Streamlit for real-time visualization.
🕒 Performance Evaluation: Displays model accuracy and error metrics.

🧩 Tech Stack

Programming Language: Python
Libraries Used: Pandas, NumPy, Matplotlib, Scikit-learn, Keras, yfinance, Streamlit

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/yourusername/Stock-Price-Prediction.git
cd Stock-Price-Prediction

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run the Streamlit app
streamlit run app/app.py

📊 How It Works

Fetches historical stock data using yfinance.
Cleans and preprocesses data (handles missing values, outliers).
Computes rolling averages over user-defined window sizes.
Uses a machine learning or deep learning model (LSTM) for price forecasting.
Displays actual vs. predicted prices through an interactive Streamlit dashboard.

📈 Example Output

Predicted vs Actual price comparison graph.
Rolling average trend visualization.
Model performance metrics (MAE, RMSE).

📊 Sample Visualization
📉 Closing Price vs Predicted Price
---------------------------------
| Date        | Actual | Predicted |
|--------------|---------|-----------|
| 2025-10-01   | 153.24 | 152.87    |
| 2025-10-02   | 154.60 | 153.92    |
| ...          |   ...  |    ...    |

🔮 Future Enhancements

Integrate real-time stock price API (e.g., Alpha Vantage).
Add sentiment analysis from financial news.
Implement Reinforcement Learning for trading strategy.

Expand dashboard with multi-stock comparison and correlation heatmaps.

🤝 Contributors
Trishna Bhowmik
