# Cycle Extraction from Financial Data

## Overview
This Jupyter notebook, `CycleExtraction.ipynb`, is designed for financial analysts and data scientists focusing on extracting cyclical components from financial time series data. Leveraging Python's powerful libraries, including NumPy, pandas, matplotlib, and MetaTrader 5, it offers a comprehensive workflow from data acquisition to analysis, emphasizing the extraction of significant cyclical patterns within market price data.

## Features
- **MetaTrader 5 Integration**: Establishes a connection with MetaTrader 5 for real-time financial market data access.
- **Data Collection and Cleaning**: Automates the collection of historical price data for specified symbols and periods, followed by data cleaning and preparation.
- **Frequency Analysis**: Utilizes Fast Fourier Transform (FFT) to identify and visualize frequency components within the data.
- **Signal Filtering**: Applies frequency-based filtering to isolate and analyze specific cyclical behaviors in the price data.
- **Trend Analysis**: Implements trend detection within the filtered signal to identify potential market movements.

## Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab
- MetaTrader 5 Terminal installed (for real-time data)
- Required Python libraries: `numpy`, `matplotlib`, `pandas`, `MetaTrader5`, `datetime`, `sklearn`

## Installation
Ensure that you have the necessary Python libraries installed. You can install them using pip:

```bash
pip install numpy matplotlib pandas MetaTrader5 sklearn
```

## Usage
1. Open the `CycleExtraction.ipynb` notebook in your Jupyter environment.
2. Ensure that MetaTrader 5 is running and connected to your trading account for real-time data access.
3. Execute the cells in sequence from top to bottom. Each cell is documented for clarity and understanding of the process.
4. Adjust the parameters as needed to fit your specific analysis requirements, such as changing the symbols or the analysis period.

## Contributing
Contributions to improve the notebook or extend its capabilities are welcome. Please feel free to fork the repository, make your changes, and submit a pull request.

## Disclaimer
This notebook is for educational purposes only and is not intended as financial advice. Always consult with a financial advisor before making investment decisions.
