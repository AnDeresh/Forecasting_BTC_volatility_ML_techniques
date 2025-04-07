# BTC Volatility Prediction

This repository provides a Jupyter Notebook for predicting BTC/USD volatility using various econometric and machine learning models. 

## Repository Structure

├── data/ 
│ └── BTCUSD_1m_Binance.csv                 # This file is not included in the repository due to its large size. 
├── btc_vol_predict.ipynb                   # Main notebook containing the analysis and modeling code 
└── requirements.txt                        # List of required Python packages

```bash
├── data/ 
│ └── BTCUSD_1m_Binance.csv             # CSV file with 1-minute BTC/USD data. Is not included in the repository due to its large size.
├── btc_vol_predict.ipynb               # Main notebook with volatility prediction code 
└── requirements.txt                    # List of required Python packages
```

### 1. `data/`
- Contains the CSV file `BTCUSD_1m_Binance.csv`, which holds historical BTC/USD data on a 1-minute interval.

### 2. `btc_vol_predict.ipynb`
- The main Jupyter Notebook demonstrating data cleaning, feature engineering, model training, and evaluation for BTC volatility prediction.

### 3. `requirements.txt`
- A list of Python dependencies needed to run the notebook. Install with:
  ```bash
  pip install -r requirements.txt

## Installation and Usage

1. Clone the repository:
```bash
git clone https://github.com/your-username/btc-vol-predict.git
```

2. Navigate to the project folder:
```bash
cd btc-vol-predict
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

4. Launch the Jupyter Notebook:
```bash
jupyter notebook btc_vol_predict.ipynb
```

5.Run the Notebook:
- Follow the instructions in the notebook to load the data, preprocess it, and train various models for BTC volatility forecasting.

## Model Overview

- Econometric Models: Includes GARCH variants for volatility forecasting.
- Machine Learning Models: Various regression models, including Random Forest, LightGBM, etc.

## Data Source
- `BTCUSD_1m_Binance.csv` provides 1-minute BTC/USD price data from Binance
- The data used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/imranbukhari/comprehensive-btcusd-1m-data).
- Note: Due to the file size (~512 MB), the CSV file is not included in this repository. Please download it from Kaggle and place it in the `data/` folder.

