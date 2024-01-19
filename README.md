# TopBottomEA Expert Advisor
This is the README file for the TopBottomEA Expert Advisor code.

## Introduction
The TopBottomEA Expert Advisor is a trading software developed by Forex Robot Easy Team. It is designed to trade in the Forex market based on the concept of identifying the top and bottom levels of price movements. This Expert Advisor aims to capture profitable trades by placing pending orders at the identified top and bottom levels.

For detailed reviews and trading results of this product, you can visit [Forex Robot Easy's website](https://forexroboteasy.com/forex-robot-review/topbottomea-forex-software-review-real-results-with-small-capital/). Please note that Forex Robot Easy is not the official developer of this product. We only provide the sample code that can work as described in the product.

## Installation
To use the TopBottomEA Expert Advisor, follow these steps:
1. Open your MetaTrader 5 platform.
2. Go to 'File' > 'Open Data Folder'. This will open the data folder of your MetaTrader 5 installation.
3. Navigate to the 'MQL5' folder.
4. Copy the 'TopBottomEA.mq5' file into the 'Experts' folder.
5. Restart your MetaTrader 5 platform.
6. The TopBottomEA Expert Advisor should now be available in the 'Expert Advisors' section of the Navigator window.

## Configuration
The TopBottomEA Expert Advisor can be configured using the following parameters:
- `stopLoss`: The stop loss value in pips.
- `capitalLimit`: The minimum capital limit in dollars.
- `maxTradesPerDay`: The maximum number of trades allowed per day.
- `tradeDuration`: The duration of each trade in hours.

## Usage
To use the TopBottomEA Expert Advisor, follow these steps:
1. Attach the Expert Advisor to a chart of your desired currency pair and timeframe.
2. The Expert Advisor will initialize and print the initialization details in the 'Experts' tab of the Terminal window.
3. The Expert Advisor will perform backtesting for more than 10 years, from the current date.
4. If the account balance is below the specified capital limit, the Expert Advisor will print an insufficient capital message and stop trading.
5. If the capital limit is met, the Expert Advisor will calculate the trade volume based on the account balance.
6. The Expert Advisor will get the current price and calculate the stop loss price based on the specified stop loss value.
7. It will then check for existing trades and pending orders.
8. If the maximum trades per day is reached, the Expert Advisor will print a maximum trades message and stop trading.
9. If there is an existing position, the Expert Advisor will close it.
10. If there is an existing pending order, the Expert Advisor will print a pending order exists message and stop trading.
11. If all conditions are met, the Expert Advisor will place a new pending order at the current price with the calculated trade volume and stop loss price.
12. The Expert Advisor will print a pending order placed successfully message if the order is placed successfully.
13. If the order placement fails, the Expert Advisor will print a failed to place pending order message with the error code.

## Expert Advisor Deinitialization
When the Expert Advisor is deinitialized, the deinitialization reason will be printed in the 'Experts' tab of the Terminal window.

For any further information or support regarding this Expert Advisor, please refer to the official developer through the MQL5 platform.
