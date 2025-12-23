# Fibonacci-RSI-Indicator
# 📊 Fibonacci 0.618 & RSI Indicator

A professional TradingView Pine Script indicator combining Fibonacci 0.618 retracement levels with RSI signals for enhanced technical analysis.

## 🌟 Features

### Fibonacci 0.618 Retracement
- **Automatic Detection**: Identifies swing highs and lows automatically
- **Dual Direction Analysis**: Shows both bullish (BUY) and bearish (SELL) 0.618 levels
- **Visual Elements**: 
  - Color-coded lines (Green for bullish, Red for bearish)
  - Price labels with exact values
  - Optional boxes around Fibonacci levels
  - Swing point markers with arrows
  - Connecting lines between swing points
- **Customizable Settings**:
  - Adjustable swing length sensitivity
  - Line width control
  - Optional line extension to the right
  - Configurable box distance from candles

### RSI (Relative Strength Index)
- **Smart Signal Generation**: Shows labels only at crossover moments
- **Overbought/Oversold Detection**:
  - Oversold signals when RSI crosses below 30 (default)
  - Overbought signals when RSI crosses above 70 (default)
- **Customizable Parameters**:
  - Adjustable RSI length (default: 14)
  - Custom overbought/oversold levels
  - Multi-timeframe support
  - Color customization for labels and text

### Alert System
Built-in alert conditions for:
- RSI Oversold conditions
- RSI Overbought conditions  
- Price crossing above bullish Fibonacci 0.618 level
- Price crossing below bearish Fibonacci 0.618 level

## 📥 Installation

1. Open TradingView and navigate to the Pine Editor
2. Create a new indicator
3. Copy and paste the code from `fibonacci_rsi_indicator.pine`
4. Click "Add to Chart"

## ⚙️ Configuration

### Fibonacci Settings
| Parameter | Default | Description |
|-----------|---------|-------------|
| Show Fibonacci 0.618 | ✓ | Enable/disable Fibonacci levels |
| Swing Length | 40 | Sensitivity for swing detection (higher = stronger swings) |
| Line Width | 2 | Thickness of Fibonacci lines |
| Extend Line to Right | ✓ | Extend lines into future |
| Box Distance from Candles | 25 | Distance of labels/boxes from last candle |
| Show Fibonacci Box | ✓ | Display boxes around Fibonacci levels |

### RSI Settings
| Parameter | Default | Description |
|-----------|---------|-------------|
| Show RSI Signals | ✓ | Enable/disable RSI signals |
| RSI Timeframe | Current | Timeframe for RSI calculation |
| RSI Length | 14 | Period for RSI calculation |
| Oversold Level | 30 | RSI level for oversold signals |
| Overbought Level | 70 | RSI level for overbought signals |
| Colors | Customizable | Label and text colors |

## 📖 How to Use

### Trading with Fibonacci 0.618
1. **Bullish Setup**: Look for price to approach the green BUY 0.618 level for potential long entries
2. **Bearish Setup**: Watch for price to reach the red SELL 0.618 level for potential short entries
3. The indicator automatically updates levels based on the most recent swing highs and lows

### Trading with RSI
1. **Oversold Signals**: Blue labels appear when RSI drops below the oversold level (potential buy opportunity)
2. **Overbought Signals**: Orange labels appear when RSI rises above the overbought level (potential sell opportunity)
3. Combine with Fibonacci levels for confirmation

### Combined Strategy
- **Best Entry Points**: When RSI oversold signal appears near Fibonacci 0.618 bullish level
- **Best Exit Points**: When RSI overbought signal appears near Fibonacci 0.618 bearish level

## 🔔 Setting Up Alerts

1. Click on the indicator name in the chart
2. Select "Create Alert"
3. Choose from available conditions:
   - RSI Oversold
   - RSI Overbought
   - Fib Buy Signal
   - Fib Sell Signal
4. Configure your notification preferences

## 📸 Screenshots

*(Add your chart screenshots here showing the indicator in action)*

## 🛠️ Technical Details

- **Version**: Pine Script v6
- **Overlay**: Yes (displays on price chart)
- **Max Lines**: 500
- **Max Labels**: 100
- **Max Boxes**: 50

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](../../issues).

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Developer

**CODE_FINANCE Team**

- 📧 Email: info.cdodefinance@gmail.com
- 💬 Telegram: [@code_finance](https://t.me/code_finance)
- 🐙 GitHub: [@CODE-FINANC](https://github.com/CODE-FINANC)

## ⭐ Support

If you find this indicator helpful, please give it a star! ⭐

## ⚠️ Disclaimer

This indicator is for educational and informational purposes only. It should not be considered as financial advice. Always do your own research and consider consulting with a qualified financial advisor before making trading decisions. Past performance does not guarantee future results.

---

**Happy Trading! 📈💰**
![Fibonacci 0.618 & RSI Indicator](docs/screenshot-1.png)
