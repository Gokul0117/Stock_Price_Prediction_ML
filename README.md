# Stock Price Prediction using Machine Learning

This project predicts stock prices using deep learning models such as **LSTM**, **CNN**, and **Transformer**.
It uses historical stock data fetched directly from Yahoo Finance and forecasts the **next day’s price**.

 Stock Price Prediction using Machine Learning

# This project predicts stock prices using deep learning models such as **LSTM**, **CNN**, and **Transformer**.  
It uses historical stock data fetched directly from Yahoo Finance and forecasts the **next day’s price**.

## Features
- Fetches real-time historical stock data using `yfinance`
- Implements **LSTM**, **CNN**, and **Transformer** models
- Compares model performances visually
- Displays actual vs predicted stock price graphs
- Built with **Python, TensorFlow, and Gradio** for interactive web deployment

## 🧩 Technologies Used
- Python 
- TensorFlow / Keras
- yfinance
- Matplotlib
- Gradio (for web app interface)

## 📊 How It Works
1. User inputs a stock ticker (e.g., AAPL, TSLA, INFY.NS)
2. Fetches past 5 years of stock data
3. Prepares dataset for deep learning models
4. Predicts the next day’s closing price
5. Displays results and graph interactively

## 💻 Run Locally
1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/Gokul0117/Stock_Price_Prediction_ML.git
   cd Stock_Price_Prediction_ML
   \`\`\`
2. Install dependencies:
   \`\`\`bash
   pip install -r requirements.txt
   \`\`\`
3. Run the Jupyter Notebook:
   \`\`\`bash
   jupyter notebook
   \`\`\`

## 📈 Future Enhancements
- Add more models like Prophet or XGBoost
- Include news sentiment analysis
- Add user-uploaded CSV support
- Deploy full web app on Streamlit or Hugging Face Spaces

## 👨‍💻 Author
**Gokul J**  
"Final Year Student, Saveetha Engineering College  
Passionate about Deep Learning, AI, and FinTech 🚀"
