# Supply and Demand Zones with Range Filter

A Pine Script indicator that combines **Supply and Demand Zones** with a **Range Filter**, designed to help traders identify key market levels, trends, and breakout opportunities. This tool is ideal for swing trading, intraday setups, and breakout strategies.

---

## Features

### 1. **Supply and Demand Zones**
- Automatically detects **Supply Zones** (resistance) and **Demand Zones** (support).
- Dynamically updates zones:
  - Removes broken zones.
  - Extends valid zones horizontally.
- Configurable zone settings:
  - Adjustable **Zone Difference Scale** to fine-tune detection.
  - Horizontal zone extension.
  - Enable or disable zones individually.
  - Customizable colors and borders for zones.
- Option to display descriptive labels inside the zones.

### 2. **Range Filter**
- Smoothed range filter for identifying trends and filtering market noise.
- Configurable parameters:
  - **Sampling Period** for range calculation.
  - **Range Multiplier** to adjust sensitivity.
- Highlights **Upward** and **Downward** trends with distinct colors.
- Plots **High Band** and **Low Band** target levels for potential breakouts or reversals.

### 3. **Breakout and Reversal Alerts**
- Provides **Buy** and **Sell** signals:
  - **Buy Signal**: Price breaks above the range filter during an upward trend.
  - **Sell Signal**: Price drops below the range filter during a downward trend.
- Visual markers:
  - Green "Buy" labels below bars.
  - Red "Sell" labels above bars.
- Alerts for automated notifications.

### 4. **Visual Enhancements**
- Colored candlesticks to indicate trend direction:
  - **Green** for upward momentum.
  - **Red** for downward momentum.
  - Neutral color for flat trends.
- Filled ranges between the filter line and high/low bands for better clarity.

---

## Installation
1. Open the TradingView platform.
2. Navigate to **Pine Script Editor**.
3. Copy and paste the script from this repository into the editor.
4. Save and add the indicator to your chart.

---

## Inputs
### Supply and Demand Zones
- **Zone Difference Scale**: Adjusts the ratio to identify significant price movements.
- **Zone Extension**: Extends zones horizontally.
- Enable or disable zones.
- Customizable colors for zones and labels.

### Range Filter
- **Source**: Select the price input (default: `close`).
- **Sampling Period**: Smoothens the range calculation (default: `100`).
- **Range Multiplier**: Adjusts filter sensitivity (default: `2.0`).

---

## Alerts
- **Buy Signals**: Triggered during upward breakouts.
- **Sell Signals**: Triggered during downward breakouts.
- Combined **Buy and Sell Alerts** for automation.

---

## How It Works
1. **Supply and Demand Zones**:
   - Zones are identified based on significant candle differences.
   - Supply zones form after large red candles, while demand zones form after large green candles.
   - Broken zones are removed dynamically to keep the chart clean.

2. **Range Filter**:
   - Tracks price movements and filters market noise.
   - Helps identify trend direction and provides visual confirmation of momentum.

3. **Alerts**:
   - Sends notifications for buy or sell conditions.
   - Signals can be used to automate trading strategies.

---

## Example Use Cases
- **Swing Trading**: Place limit orders near supply or demand zones for high-probability entries.
- **Trend Following**: Confirm trend direction using the range filter to avoid choppy markets.
- **Breakout Trading**: Act on buy or sell signals for intraday or scalping setups.

---

## Customization
Feel free to modify the script to suit your specific trading needs. Input parameters can be adjusted to optimize performance for different instruments or timeframes.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Credits
Developed by **Mihir Madkaikar**. Designed to enhance decision-making for traders across all markets. For any suggestions or improvements, feel free to contribute or open an issue.

---

## Contact
For inquiries or feedback, reach out to me via GitHub or email.
