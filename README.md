
# Stock Price Prediction using LSTM

This project is designed to predict stock prices using a Long Short-Term Memory (LSTM) model, implemented using TensorFlow's Keras library. The project was developed as part of a challenge and aims to forecast stock prices based on historical data.

## Project Overview

The objective of this project is to utilize historical stock data to predict future stock prices using a machine learning model. The model is trained on a dataset containing stock prices over a period of time, and it uses LSTM, a type of recurrent neural network (RNN) well-suited for time series data.

## Features

- **Data Preprocessing**: The stock data is preprocessed using techniques such as scaling to ensure that the model receives normalized data.
- **LSTM Model**: The model is built using LSTM layers, which are effective in capturing temporal dependencies in sequential data.
- **Prediction**: After training, the model is used to predict stock prices, and its performance is evaluated using appropriate metrics.

## Dataset

The dataset used in this project is a CSV file containing the following columns:

- **Date**: The date of the stock price.
- **Open**: The opening price of the stock on the given date.
- **High**: The highest price of the stock on the given date.
- **Low**: The lowest price of the stock on the given date.
- **Close**: The closing price of the stock on the given date.
- **Adj Close**: The adjusted closing price of the stock, taking into account factors like dividends.
- **Volume**: The number of shares traded on the given date.

## Model Architecture

The model architecture consists of:

- **LSTM Layers**: To capture the time dependencies in the stock prices.
- **Dense Layers**: To process the output from the LSTM layers and make the final prediction.
- **Dropout Layers**: To prevent overfitting during training.

## Installation and Usage

### Prerequisites

- Python 3.x
- TensorFlow
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

### Installation

To install the necessary packages, run:

```bash
pip install -r requirements.txt
```

### Usage

1. Clone this repository:

```bash
git clone https://github.com/your-username/stock-prediction-lstm.git
cd stock-prediction-lstm
```

2. Ensure that the `stock.csv` file is in the root directory.

3. Run the Jupyter notebook to train the model:

```bash
jupyter notebook projectstocknewgoogle.ipynb
```

4. The notebook will guide you through the data preprocessing, model training, and evaluation steps.

## Results

The model's predictions are plotted against the actual stock prices to visually evaluate the model's performance. The accuracy and other evaluation metrics are also computed to quantify the model's effectiveness.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
