# Advanced Indicator Scanner MT5

This code is an advanced indicator scanner for the MetaTrader 5 platform. It allows users to scan and monitor chosen indicators across multiple symbols and timeframes. The scanner supports customization and access to hundreds of custom indicators available on the web.

## Features

- Scans and monitors indicators across multiple symbols and timeframes.
- Supports customization and access to custom indicators available on the web.
- Provides trading actions based on scanner results.

## Developer Information

- Developer: Forex Robot Easy Team
- Website: [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/review-advanced-indicator-scanner-mt5-a-powerful-multi-symbol-multi-timeframe-forex-software/)
- For detailed reviews and trading results of this product, please visit the [Forex Robot Easy website](https://forexroboteasy.com/forex-robot-review/review-advanced-indicator-scanner-mt5-a-powerful-multi-symbol-multi-timeframe-forex-software/).

## Code Description

### Libraries Used

This code utilizes the following libraries:
- Trade.mqh
- Indicator.mqh

### Scanner Parameters

The scanner parameters are defined as follows:
- `MAX_SYMBOLS`: Maximum number of symbols to scan.
- `MAX_TIMEFRAMES`: Maximum number of timeframes to scan.
- `MAX_LINES`: Maximum number of lines to scan.

### Scanner Initialization

The scanner is initialized using the `CIndicatorScanner` class.

### Scanner Setup

The scanner parameters are set using the `SetIndicatorParameters` method of the `CIndicatorScanner` class. The parameters include the symbols, timeframes, and number of lines to scan.

### Custom Indicators

Custom indicators from the web can be added to the scanner using the `AddIndicator` method of the `CIndicatorScanner` class. In this code, two custom indicators, 'CustomIndicator1' and 'CustomIndicator2', are added.

### Indicator Scanning and Monitoring

The scanner scans and monitors the indicators using the `ScanIndicators` and `MonitorIndicators` methods of the `CIndicatorScanner` class, respectively.

### Trading Actions

Based on the scanner results, trading actions can be performed. In this code, if the indicator 'CustomIndicator1' crosses 'CustomIndicator2', a trade is opened using the `CTrade` class.

## Disclaimer

Please note that Forex Robot Easy is not the official developer of this product. The code provided here is a sample that can work as described in the product. To find the official developer of this product, please use the MQL5 platform. For detailed reviews and trading results, please visit the [Forex Robot Easy website](https://forexroboteasy.com/forex-robot-review/review-advanced-indicator-scanner-mt5-a-powerful-multi-symbol-multi-timeframe-forex-software/).
