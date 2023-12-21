# Night Theft Forex Software

This is the code for the Night Theft Forex Software, developed by the Forex Robot Easy Team. For detailed reviews and trading results of this product, please visit [this link](https://forexroboteasy.com/forex-robot-review/night-theft-forex-software-review-of-overnight-trading-success/).

## Introduction
Night Theft Forex Software is an automated trading system designed to trade the forex market during specific night hours. It utilizes the Super Smart Trend catcher algorithm to analyze the market and open trades based on trend detection.

## Features
- Trading during specific night hours
- Super Smart Trend catcher algorithm for market analysis
- Adjustable lot size, take profit, and stop loss levels
- Recovery martingale mode for additional orders
- Easy integration with the MetaTrader 4 platform

## Installation
To use the Night Theft Forex Software, follow these steps:

1. Import the necessary libraries: `Trade.mqh` and `Timeseries.mqh`
2. Define the required constants, such as night start and end hours, lot size, take profit, stop loss, and recovery mode multiplier.
3. Initialize the global variables: `trade` and `series`.
4. Implement the `OnTick` function as the entry point of the program. Inside this function, check if it is night time and if a trend is detected. If both conditions are met, open a new order using the `OpenOrder` function.
5. Implement the `IsNightTime` function to check if it is night time based on the current hour.
6. Implement the `IsTrendDetected` function to analyze the market and detect trends using the Super Smart Trend catcher algorithm.
7. Implement the `OpenOrder` function to open a new market order. If the order is opened successfully, check if recovery martingale mode is enabled and place additional recovery orders if necessary.
8. Implement the `IsRecoveryModeEnabled` function to check if recovery martingale mode is enabled.
9. Initialize the program in the `OnInit` function by setting the expert magic number and configuring the trade and series objects.
10. Clean up and release resources in the `OnDeinit` function.

Please note that ForexRobotEasy is not the official developer of this product. This code is provided as a sample and may require additional modifications or customization to work as described in the product. To find the official developer of this product, please refer to MQL5.

## Disclaimer
Forex trading involves significant risk of loss and is not suitable for all investors. The Night Theft Forex Software is an automated trading system and its performance may vary. Past performance is not indicative of future results. It is recommended to test the software on a demo account before using it with real funds. ForexRobotEasy does not provide any guarantees or warranties regarding the performance or accuracy of this product. Users should use their own discretion and judgment when using this software.
