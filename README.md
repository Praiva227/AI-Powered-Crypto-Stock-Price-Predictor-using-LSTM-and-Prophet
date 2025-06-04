cat << 'EOF' > README.md
# Stock & Crypto Price Predictor Using LSTM and Prophet

This Streamlit web app predicts stock and cryptocurrency prices using two models: LSTM (deep learning) and Prophet (statistical). It fetches real-time and historical data from Yahoo Finance and lets users select assets, choose the model, and visualize forecasts with interactive charts.

## Features
- Predict prices for 25+ stocks and 24+ cryptocurrencies
- Choose between LSTM and Prophet models
- Real-time data from Yahoo Finance
- Interactive charts and performance metrics (R², MAE)
- User-friendly dashboard for model comparison

## How to Run

1. Clone this repo and enter the folder:
    git clone <repository_url>
    cd <repository_folder>

2. Install dependencies:
    pip install -r requirements.txt

3. Start the app:
    streamlit run app.py

## Usage

- Select asset type (Stock or Cryptocurrency)
- Choose a symbol or enter your own
- Select the prediction model (LSTM or Prophet)
- Set prediction days and training options
- Click “Generate Predictions” to view results

EOF
