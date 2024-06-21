
# Stock Prediction Application using LSTM RNN

This is a stock prediction application that utilizes an LSTM (Long Short-Term Memory) Recurrent Neural Network to predict stock prices. The application is built using various Python packages and is presented through a Streamlit web interface.


## Table of Contents

- Features
- Installation
- Usage
- Packages Used
- Project Structure
- License


## Features
- Fetches stock data using yfinance and pandas_datareader
- Preprocesses data with numpy, pandas, and sklearn
- Builds and trains an LSTM RNN model using tensorflow and keras
- Visualizes stock data and prediction results using matplotlib
- User-friendly web interface built with streamlit
## Installation

1. Clone the repository:

```bash
  git clone https://github.com/deySucil/PythonProject_RNN.git  
```

2. Install the required packages:
```bash
  pip install -r requirements.txt

```
## Usage

1. Run the Streamlit application:

```bash
  streamlit run app.py 
```

2. Follow the prompts on the Streamlit interface to select the stock ticker and date range for prediction.
## Packages Used

- numpy: For numerical operations
- pandas: For data manipulation
- matplotlib.pyplot: For data visualization
- pandas_datareader: For fetching stock data
- yfinance: For fetching stock data
- sklearn.preprocessing: For data preprocessing
- tensorflow: For building and training the LSTM model
- keras.layers: For defining LSTM layers
- keras.models: For creating the LSTM model
- streamlit: For creating the web interface
