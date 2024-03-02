# Full Fractals MT5

This code is a custom indicator that identifies and displays fractal levels on a forex chart. Fractals are points on the chart that indicate potential price reversal points. The indicator draws arrows on the chart to mark the fractal levels.

## Input Parameters

- `LeftCandles`: Number of candles to the left of the main candle to consider for fractal calculation.
- `RightCandles`: Number of candles to the right of the main candle to consider for fractal calculation.
- `UpArrowColor`: Color for up arrows.
- `DownArrowColor`: Color for down arrows.
- `ArrowSize`: Size of the arrows.

## Global Variables

- `prevFractal`: Previous fractal level.
- `prevSupportLevel`: Previous support level.
- `prevResistanceLevel`: Previous resistance level.

## Custom Indicator Initialization

The `OnInit()` function is called when the indicator is initialized. In this function, the indicator buffers are set and the indicator label is defined.

## Custom Indicator Calculation

The `OnCalculate()` function is called for each new bar on the chart. This function calculates the main fractal level and checks if a new fractal is formed. If a new fractal is detected, the function determines if it is an up fractal or a down fractal. It also sets the previous support and resistance levels accordingly. Arrows are then drawn on the chart to indicate the fractal levels.

## Custom Indicator Deinitialization

The `OnDeinit()` function is called when the indicator is removed from the chart. In this function, the indicator buffers are cleared.

---

## Product Description

Full Fractals MT5 is a custom indicator designed to help traders identify potential price reversal points on forex charts. Fractals are powerful tools that can indicate the beginning of a new trend or a reversal in the current trend.

With Full Fractals MT5, traders can easily spot these important fractal levels on their charts. The indicator draws arrows to highlight the fractal levels, making it easy for traders to identify potential entry and exit points.

By using Full Fractals MT5, traders can make more informed trading decisions and improve their overall trading performance. Whether you are a beginner or an experienced trader, this indicator can be a valuable addition to your trading toolkit.

Please note that Forex Robot Easy is not the official developer of this product. We only provide this sample code to demonstrate how the indicator works. To find the official developer of this product and access detailed reviews and trading results, please visit [Forex Robot Easy - Full Fractals MT5 Review](https://forexroboteasy.com/forex-robot-review/full-fractals-mt5-review-unveiling-price-reversal-points/).

To use this indicator, you can download it from the official MQL5 website and install it on your MetaTrader 5 trading platform.
