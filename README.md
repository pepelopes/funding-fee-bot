# 🤖 funding-fee-bot - Automate Your AsterDex Trading

[![Download](https://img.shields.io/badge/Download-latest%20release-brightgreen)](https://github.com/pepelopes/funding-fee-bot/releases)

## 📦 Introduction
Welcome to the AsterDex Funding Bot! This is a simple tool that helps you automate your trading strategies on AsterDex. With this bot, you can easily manage your funding fees, whether you want to buy spot or short futures. 

## 🚀 Getting Started
To get started with the funding bot, follow these steps. You will need some basic requirements listed below.

### 📋 Requirements
- **Python 3.9 or higher**: This script runs with Python. Make sure you have it installed on your computer.
- **Requests Library**: The bot needs the `requests` library. You can install it using pip.
- **AsterDex Account**: Make sure you have an AsterDex account with an API Key, Secret, and enough funds loaded.

### 💻 Download & Install
You can easily download the latest version of the funding fee bot by visiting the Releases page. Click the button below to download:

[![Download](https://img.shields.io/badge/Download-latest%20release-brightgreen)](https://github.com/pepelopes/funding-fee-bot/releases)

Once downloaded, extract the files to a folder on your computer. 

### 🔧 Code Setup
You may want to customize some of the default settings. Open the `funding_bot.py` file and look for these lines to adjust:
```python
DEFAULT_CAPITAL_USD = Decimal("200000")
DEFAULT_SPOT_SYMBOL = "ASTERUSDT"
DEFAULT_FUTURES_SYMBOL = "ASTERUSDT"
DEFAULT_BATCH_QUOTE = Decimal("200")
DEFAULT_BATCH_DELAY = 1.0
```
Feel free to change these values based on your trading needs.

## ⚙️ Running the Bot
To run the bot, follow these steps:

1. Open your terminal or command prompt.
2. Navigate to the folder where you extracted the bot.
3. Type the command below and hit enter:
   ```bash
   python funding_bot.py --mode [buy_spot|short_futures|sell_spot|long_futures]
   ```
   Replace `[buy_spot|short_futures|sell_spot|long_futures]` with your desired trading direction.

## 🔍 Monitoring Trades
The bot will automatically send orders while checking the status of each order. You can view the activity log in your console. It will show the current status of your trades clearly.

## ⚡ Features
- **Automated Trading**: Sends orders in pairs with optional delays.
- **Order Fulfillment Monitor**: Keeps track of order status until confirmed.
- **Custom Settings**: Adjust API keys and important parameters in the file or through command line.
- **Detailed Logging**: Color-coded logs provide a clear view of what the bot is doing.
- **Flexible Trading Direction**: Choose your trading direction with the `--mode` option.

## 🚨 Troubleshooting
If you encounter issues running the bot, check the following:

- Make sure Python is properly installed. You can verify this by running `python --version`.
- Ensure that the `requests` library is installed. If not, install it by running:
  ```bash
  pip install requests
  ```
- Verify that your AsterDex account is active and has sufficient funds.

## 📞 Support
For additional help or to report issues, feel free to open an issue on this GitHub repository. We strive to improve your experience and welcome any feedback.

## 📅 Updates
Keep an eye on the Releases page to download the latest updates and features. Regular improvements will enhance performance and fix any bugs.

[![Download](https://img.shields.io/badge/Download-latest%20release-brightgreen)](https://github.com/pepelopes/funding-fee-bot/releases)

Enjoy automating your trading with the Funding Fee Bot!