# Short-Term Trading With Transformers
This project creates a Transformer model with the purpose of forecasting future intra-day stock opening prices for multi-resolution time-steps. This model performs best on data from indices and exchange rates where stock prices are rendered at 1-minute time-step candlesticks.

# Optimizations

This transformer model uses the follwing optimizations for Time-Series Forecasting:

- Multi-Scale Gaussian Prior Bias and Time-Splitter Gap Masking per Attention Heads (Ding et al., 2021)

# References

Ding, Q., Wu, S., Sun, H., Guo, J., & Guo, J. (2021). Hierarchical multi-scale Gaussian transformer for stock movement prediction. *Proceedings of the Twenty-Ninth International Joint Conference on Artificial Intelligence* (pp. 4640-4646). Yokohama, Yokohama, Japan.