
# LIC Stock Price Analysis

Stock price analysis and prediction for LIC (Life Insurance Corporation of India).

## Dataset

**Source:** [LIC Stock Price Data](https://www.kaggle.com/datasets/debashis74017/lic-stock-price-data)

### About the Dataset
This dataset contains historical stock price data for LIC at multiple time intervals, enabling both long-term trend analysis and short-term trading pattern recognition.

## Files

- `lic.ipynb` - Main analysis notebook
- `LICI - Daily data.csv` - Daily stock price data
- `LICI - 10 minute data.csv` - 10-minute interval data
- `LICI - 5 minute data.csv` - 5-minute interval data
- `LICI - 3 minute data.csv` - 3-minute interval data
- `LICI - minute ata.csv` - Minute-level data

## Setup Instructions

1. The dataset files are already included in this folder. If you need to refresh the data:
   - Visit: https://www.kaggle.com/datasets/debashis74017/lic-stock-price-data
   - Download the latest version
   - Replace the CSV files in this folder

2. Install required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. Open and run the notebook:
   ```bash
   jupyter notebook lic.ipynb
   ```

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Analysis

The notebook includes:
- Time series analysis of stock prices
- Technical indicators calculation
- Price trend visualization
- Predictive modeling for stock prices
- Multiple timeframe analysis (daily, 10-min, 5-min, 3-min, 1-min)
