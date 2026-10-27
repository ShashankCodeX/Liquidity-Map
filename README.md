# Liquidity Map [LW]

A TradingView Pine Script v5 overlay indicator that maps swing liquidity, equal highs and lows, and previous day and week levels.

## Features

- Plots pivot swing high and low levels, updating their line style as they age and removing them after price closes through them.
- Detects equal highs and equal lows using a configurable percentage sensitivity.
- Marks previous day high and low, plus previous week high and low.
- Includes a chart legend for sell-side, buy-side, equal-level, previous-day, and previous-week liquidity.

## Use

1. Open [TradingView](https://www.tradingview.com/).
2. Open the Pine Editor and paste the contents of [liquidity-map.pine](./liquidity-map.pine).
3. Select **Add to chart**.

## Inputs

Adjust the swing length, visibility of swing and equal levels, equal-level sensitivity, and previous day/week levels in the indicator settings.

## Notes

The script is provided as-is. Its levels are based on the rules in the source and should be evaluated on your chart and timeframe; this repository does not make a performance or accuracy guarantee.

## License

Licensed under the MIT License; see [LICENSE](./LICENSE).
