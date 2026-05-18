# Repository

Companion code for a Medium article.

## Business context

Time series analysis models need to account for temporal dependencies (e.g., ARIMA, exponential smoothing, and state-space methods). Additionally, time series values are measured at some frequency but may require resampling or aggregation to a different frequency for analysis.

Traditional parametric statistics assume the underlying data is stationary---that is, the mean, variance, and autocorrelation remain constant over time. However, time series data often exhibits changing trends, requiring different feature engineering techniques such as lagged features, rolling statistics, or derivatives to embed temporal patterns into models.

## Disclaimer

Educational/demo code only. Not financial, safety, or engineering advice. Use at your own risk. Verify results independently before any production or operational use.

## License

MIT — see [LICENSE](LICENSE).