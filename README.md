# Algorithmic Trading System Using LSTM

## Introduction
This project focuses on developing an algorithmic trading system leveraging LSTM (Long Short-Term Memory) networks. The goal is to predict stock market trends and automate trading decisions, using Python and libraries like Keras, yfinance, and Alpaca Trade API.

## Repository Structure
- `main.py`: The main Python script implementing the trading algorithm.
- `lstm_model.py`: Contains the LSTM model architecture and training functions.
- `data_processing.py`: Scripts for data retrieval and preprocessing.
- `trading_functions.py`: Includes trading-related functions like order execution.
- `requirements.txt`: List of dependencies.
- `README.md`: This file, containing project information and setup instructions.

## Setup Instructions
1. Clone the repository: `git clone https://github.com/TarmacL/Algorithmic-Trading-System`
2. Navigate to the project directory: `cd [project_directory]`
3. Install dependencies: `pip install -r requirements.txt`
4. Set your Alpaca API keys in `main.py`.
5. Run the script: `python main.py`

## Code Explanation
- `lstm_model.py` defines the LSTM neural network, responsible for learning and predicting stock market trends.
- `data_processing.py` handles the fetching and preparation of historical market data.
- `main.py` integrates all components, orchestrating data retrieval, model training, prediction, and trading.

## Usage Examples
- Run `main.py` to start the trading loop. It will automatically handle data retrieval, model management, and trade execution.
- Modify `symbol` in `main.py` to change the target stock for trading.

## Results and Screenshots
- The algorithm's performance can be evaluated using metrics like accuracy and return on investment (ROI).
- Screenshots of the algorithm's predictions and trades can be added here.

## Contributing Guidelines
Contributions are welcome! If you would like to contribute:
- Submit issues for bugs or suggestions.
- Propose enhancements via pull requests.
- Ensure your code adheres to the project's coding standards.
