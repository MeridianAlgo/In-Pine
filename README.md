# MeridianAlgo/In-Pine

MeridianAlgo offers machine-learning-driven trading tools in Pine Script for TradingView, empowering traders with adaptive, data-driven insights. As a non-profit, MeridianAlgo focuses on research and development, providing open-source tools without financial gain.

## 🌟 Overview

This repository contains Pine Script tools for technical analysis and algorithmic trading on TradingView, leveraging adaptive algorithms like RSI and moving averages (MA) for stocks and cryptocurrencies.

## ✨ Features

- **Adaptive Indicators**:
  - Dynamically optimizes RSI and MA (SMA, EMA, WMA, Hull, ALMA, RMA, LINREG, VWMA) based on market data.
  - Uses R-squared and custom scoring for performance evaluation.
  - Outputs "Bullish," "Bearish," or "Neutral" trends.
- **Customizable Settings**:
  - Adjust source data (`Close`, `Open`), RSI/MA parameters, and gradient colors.
  - Toggle adaptive RSI/MA (`useOptimalRSI`, `useOptimalMA`).
- **Visual Outputs**:
  - Gradient-colored RSI lines and signal plots (e.g., `Quantum Pulse`).
  - `Quantum Insights` table for trend direction and MA performance.
- **Non-Profit Focus**: Open-source tools for research; no commercial use.

## ⚙️ Prerequisites

- TradingView account (free or premium).
- Basic familiarity with Pine Script and TradingView’s Pine Editor.

## 📦 Installation

### Option 1: Manual Setup
1. Clone or download the repository:
   ```bash
   git clone https://github.com/MeridianAlgo/In-Pine.git
   ```
2. Open TradingView’s Pine Editor.
3. Copy and paste a script from the repository.
4. Click “Add to Chart” and customize settings (e.g., RSI length, MA type).

### Option 2: TradingView Library
1. Open TradingView.
2. Search for “MeridianAlgo” in the Indicators menu.
3. Select a tool, add to chart, and configure settings.

## 🚀 Usage

1. **Configure Settings**:
   - Adjust inputs (e.g., source data, RSI/MA lengths) via the indicator’s settings panel.
   - Enable/disable adaptive features (`useOptimalRSI`, `useOptimalMA`).
   - Customize visuals (gradient colors, table position).
2. **Monitor Outputs**:
   - View signals and edit code :)

## ⚠️ Disclaimers

- **Not Financial Advice**: For research/educational purposes only. Not a recommendation to buy/sell securities or cryptocurrencies.
- **Use at Your Own Risk**: MeridianAlgo is not liable for any losses or issues from using these tools.
- **No Real Money**: Designed for analysis, not live trading.

## 📝 Notes

- Scripts are compatible with TradingView’s Pine Script v5.
- Test on historical data before use.
- Report issues or suggest features via GitHub Issues.

## 🏗️ Contribution

Join our open-source research:
1. Fork the repository.
2. Create a feature/bug-fix branch.
3. Follow Pine Script coding guidelines.
4. Submit a pull request with clear descriptions.

## 📄 License

Mozilla Public License 2.0

## Acknowledgments

- Built by MeridianAlgo with ❤️.
- Inspired by the TradingView community and advanced ML techniques.

## About

MeridianAlgo is a non-profit dedicated to advancing algorithmic trading research through open-source Pine Script tools.

© 2025 MeridianAlgo
