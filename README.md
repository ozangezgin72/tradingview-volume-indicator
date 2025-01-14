# Volume Sum Indicator (Pine Script v5)

This Pine Script indicator calculates the total volume for a specified number of candles, considering:
- **Positive volume:** Added for bullish candles (close > open).
- **Negative volume:** Subtracted for bearish candles (close < open).
- **Neutral volume:** No change for neutral candles (close == open).

## Features
- **Customizable Candle Range:** Specify the number of candles to calculate the total volume using the `Mum Sayısı` input.
- **Dynamic Visualization:** The total volume is displayed as a line on a separate panel with a zero baseline.
- **Support for Various Assets:** Works with any asset on TradingView.

## Formula
- **Bullish Candle:** `Total Volume += Volume`
- **Bearish Candle:** `Total Volume -= Volume`
- **Neutral Candle:** `Total Volume = Unchanged`

## Usage
1. Copy the code from `volume_sum_indicator.pine`.
2. Open TradingView and navigate to the Pine Script Editor.
3. Paste the code, save, and add it to your chart.

---

## Sample Output
- **Blue Line:** Displays the cumulative volume difference for the specified candles.
- **Dashed Zero Line:** Highlights the neutral point.
