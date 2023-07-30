# Stock Price Forecasting using Deep Learning

This project aims to forecast stock prices using a deep learning model based on historical data. The model utilizes a sequence-to-sequence architecture with attention mechanisms for time series forecasting. The implementation is done using TensorFlow.

## Prerequisites

Make sure you have the following installed:

- Python 3.x
- TensorFlow
- Numpy
- Matplotlib
- Seaborn
- Pandas
- Scikit-learn

You can install the required libraries using the following command:

```bash
pip install tensorflow numpy matplotlib seaborn pandas scikit-learn
```

## Getting Started

1. Clone the repository to your local machine:

```bash
git clone https://github.com/adimis-ai/cnn-seq2seq_stock_market_prediction.git
```

2. Download the dataset:

   The dataset used for this project can be found in the dataset directory. Make sure to place the dataset file `GOOG-year.csv` in the correct location (`../dataset/GOOG-year.csv`), relative to the location of the Python script.

3. Open the Python script `stock_forecasting.py` in your preferred Python IDE or text editor.

4. Execute the Python script to run the stock price forecasting model.

## Usage

The script defines a deep learning model and uses it to forecast stock prices based on historical data. The model is trained using the training dataset and tested on the test dataset.

Please note that the training process might take some time, depending on your hardware and the number of epochs specified in the script.

## Results

The script will generate a plot showing the forecasted stock prices (based on 10 simulations) and the true stock prices from the test dataset. The average accuracy of the forecasts will also be displayed on the plot.

## License

This project is licensed under the MIT License.

## Acknowledgments

The code for the deep learning model is based on the work of [Author's Name](https://link-to-original-work-if-applicable).
