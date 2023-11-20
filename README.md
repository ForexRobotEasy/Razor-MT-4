README

# Razor MT4 Expert Advisor

Razor MT4 is a Forex trading expert advisor developed by the Forex Robot Easy Team. It is designed to implement a high precision scalping mechanism and a grid mechanism for trading in the Forex market.

## Installation

1. Download the Razor MT4 Expert Advisor from [ForexRobotEasy.com](https://forexroboteasy.com/forex-robot-review/review-razor-mt4-forex-software-real-results-and-download-available/).
2. Open your MetaTrader 4 platform.
3. Go to 'File' > 'Open Data Folder'.
4. Open the 'MQL4' folder.
5. Open the 'Experts' folder.
6. Copy the downloaded RazorMT4.ex4 file into the 'Experts' folder.
7. Restart your MetaTrader 4 platform.
8. Open the 'Navigator' window (Ctrl + N).
9. Expand the 'Expert Advisors' section.
10. Drag and drop the Razor MT4 Expert Advisor onto the chart you want to trade.

## Expert Advisor Parameters

- LotSize: The trading lot size (default: 0.01).
- StopLoss: The stop loss level in pips (default: 100.0).
- TakeProfit: The take profit level in pips (default: 200.0).

## How It Works

The Razor MT4 Expert Advisor executes trading logic based on market conditions. It consists of the following main functions:

1. `OnInit()`: This function is called during the initialization of the Expert Advisor. You can add any initialization code here.

2. `OnDeinit(const int reason)`: This function is called during the deinitialization of the Expert Advisor. You can add any deinitialization code here.

3. `OnTick()`: This function is called on each tick of the market. The trading logic code is implemented here. It checks for a new bar formation and strong market movement of AUD, CAD, and NZD currencies. If the conditions are met, it executes the high precision scalper mechanism and grid mechanism.

4. `IsNewBar()`: This function checks if a new bar has formed. You can customize this function to fit your trading strategy.

5. `IsStrongMovement()`: This function checks for strong market movement of AUD, CAD, and NZD currencies. You can customize this function to fit your trading strategy.

6. `ScalperMechanism()`: This function implements the high precision scalper mechanism. It sends buy and sell orders with the specified lot size, stop loss, and take profit levels.

7. `GridMechanism()`: This function implements the grid mechanism. It sends buy and sell orders with the specified lot size, stop loss, and take profit levels, following a grid pattern with a defined grid step and limit.

Please note that Forex Robot Easy is not the official developer of this product. We only provide the sample code that can work as described in this product. To find the official developer of this product, you can visit the MQL5 website.

For detailed reviews and trading results of this product, please visit [ForexRobotEasy.com](https://forexroboteasy.com/forex-robot-review/review-razor-mt4-forex-software-real-results-and-download-available/).

## Disclaimer

Please note that trading in the Forex market involves substantial risk of loss and is not suitable for all investors. The Razor MT4 Expert Advisor is provided for educational and informational purposes only. The Forex Robot Easy Team and its affiliates do not guarantee any specific trading results and shall not be held responsible for any losses incurred while using the Expert Advisor.

For further information and support, please visit [ForexRobotEasy.com](https://forexroboteasy.com/).
