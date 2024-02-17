# LegendsHunter

LegendsHunter is a Forex trading robot that aims to provide low capital investors with a smart and efficient trading solution. This code is a sample implementation of the LegendsHunter trading strategy. Please note that ForexRobotEasy is not the official developer of this product, and this code is only provided as a demonstration.

## About LegendsHunter

LegendsHunter is designed to identify trading opportunities based on the crossover of two moving averages - a fast moving average and a slow moving average. The robot opens buy positions when the fast moving average is above the slow moving average, and sell positions when the fast moving average is below the slow moving average.

## Input Parameters

- `initialDeposit` - The initial deposit amount for the trading account.
- `timeframe` - The timeframe for the trading analysis.
- `fastMAperiod` - The period for the fast moving average.
- `slowMAperiod` - The period for the slow moving average.

## Initialization

The `OnInit` function is responsible for initializing the trading robot. It calculates the lot size based on the initial deposit and sets up the indicators for the fast and slow moving averages.

## Trading Logic

The `OnTick` function is executed on every tick of the market. It calculates the values of the fast and slow moving averages using the `iMA` function. If the fast moving average is above the slow moving average, a buy position is opened. If the fast moving average is below the slow moving average, a sell position is opened. If a position of the opposite type is already open, it is closed before opening a new position.

## Closing Positions

The `OnDeinit` function is executed when the trading robot is removed from the chart. It closes all open positions to ensure that no positions are left open.

## Product Description

LegendsHunter is a smart Forex trading robot developed by the Forex Robot Easy Team. It is designed for low capital investors who are looking for an efficient and automated trading solution. The robot uses a proven strategy based on the crossover of two moving averages to identify profitable trading opportunities.

LegendsHunter is suitable for traders of all levels of experience. It is easy to set up and can be used on any MetaTrader 5 trading platform. The robot automatically calculates the lot size based on the initial deposit, allowing traders to effectively manage their risk.

To learn more about LegendsHunter and see detailed reviews and trading results, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/legendshunter-review-smart-forex-software-for-low-capital-investors/). Please note that ForexRobotEasy is not the official developer of this product. To find the official developer of LegendsHunter, please use the MQL5 marketplace.
