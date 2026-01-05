# ds_aarsh_khadgi
# Web3 Assignment : Trader Behavior Analysis under Fear & Greed Market Sentiment

## Overview
This project analyzes the relationship between trader behavior and market sentiment using historical cryptocurrency trading data and the Bitcoin Fear & Greed Index. The objective is to understand how profitability, trading activity, risk exposure, and transaction costs vary under Fear and Greed market conditions.

---

## Datasets
1. Bitcoin Fear & Greed Index  
   Columns: Date, Classification (Fear / Greed)

2. Historical Trader Data (Hyperliquid)  
   Columns include Account, Coin, Execution Price, Size USD, Side, Timestamp IST, Closed PnL, Fee

---

## Data Processing
- Converted date and timestamp columns to datetime format
- Reduced timestamps to daily granularity
- Merged trader data with sentiment data using trade_date
- Removed records without valid sentiment labels

---

## Visualizations
The following visualizations were created to support the analysis and are stored in the `outputs/` directory:
- Bar chart showing average profit by market sentiment
- Bar chart showing number of trades under Fear and Greed
- Stacked bar chart comparing Buy vs Sell behavior by sentiment
- Scatter plot of trade size versus profitability
- Scatter plot of transaction fees versus profitability

These graphs help identify behavioral patterns, risk exposure, and cost impact under different market sentiment conditions.

---

## Analysis Performed
The analysis focuses on:
- Average profit by market sentiment
- Number of trades under Fear and Greed
- Buy vs Sell behavior comparison
- Trade size versus profitability
- Transaction fee impact on profit

---

## Key Insights
- Traders are generally more profitable during Greed periods
- Trade activity increases during Greed and decreases during Fear
- Fear periods show more defensive trading behavior
- Larger trades increase both profit potential and risk
- Transaction fees reduce overall profitability

---

## Usage
- Open `notebook_1.ipynb` in Google Colab
- Run all cells in order
- Visual outputs are saved in the `outputs` folder
- Processed data is saved in the `csv_files` folder

---

## Report
The final summarized insights and explanations are available in `ds_report.pdf`.
