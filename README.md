# 📊 NIFTY 50 Intraday Dataset for Reinforcement Learning in Trading

This repository provides training and test datasets curated from the NIFTY 50 index for research and experimentation in algorithmic trading using reinforcement learning models such as Deep Q-Networks (DQN).

## 📁 Dataset Files

- `Nifty50_train.csv`: Preprocessed dataset for training models.
- `Nifty50_test.csv`: Corresponding test dataset used for evaluation.

## 📈 Data Description

Each row in the dataset represents a 15-minute intraday candle and contains the following columns:

- `date`: Date of the record
- `time`: Time of the candle (IST)
- `close`: Closing price
- `open`: Opening price
- `high`: Highest price during the interval
- `low`: Lowest price during the interval
- `pivot`: Pivot point (average of high, low, and close for the candle)
- `200_EMA`: 200-period Exponential Moving Average
- `Supertrend(12,3)`: Supertrend indicator with period 12 and multiplier 3
- `Supertrend(11,2)`: Supertrend indicator with period 11 and multiplier 2
- `Supertrend(10,1)`: Supertrend indicator with period 10 and multiplier 1

## 🔍 Use Case

These datasets were used in experiments involving Deep Reinforcement Learning models (DQN variants) to evaluate trading strategies on the NIFTY 50 index.

## 📌 Citation and Acknowledgment

If you use this dataset in your research, please cite the repository and acknowledge as follows:

> "This dataset was used for developing and testing reinforcement learning models for algorithmic trading on the NIFTY 50 index."

During the preparation of related research, the authors used the AI tool **ChatGPT (GPT-4)** to assist with grammar correction, language refinement, and improving readability. The authors take full responsibility for the content.

## 🛠️ License

This dataset is shared for academic and research purposes only. Please check exchange guidelines and data usage policies before using in production systems.

## Dataset Source:
The dataset (Date, Time, Open, High, Low and Close) was extracted using the Zerodha Kite Connect API under a valid paid subscription held by the author.

## Disclaimer:
While every effort has been made to ensure the accuracy and reliability of the data, it is provided as is and should be used strictly for academic and research purposes only. The author does not accept any liability or responsibility for any losses, damages, or consequences arising from the use of this dataset in live trading or commercial applications.
