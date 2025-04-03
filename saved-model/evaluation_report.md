# Model Evaluation Report

## Regression Metrics

- **Root Mean Squared Error (RMSE)**: 8963.29
- **Mean Absolute Error (MAE)**: 4247.23
- **Mean Absolute Percentage Error (MAPE)**: 18.57%
- **R² Score**: 0.8785
- **Explained Variance**: 0.8801

## Error Distribution

- **Median Absolute Error**: 1959.01
- **Maximum Error**: 292985.58

### Error Percentiles

- **25th Percentile**: 629.86
- **50th Percentile**: 1959.01
- **75th Percentile**: 4584.13
- **90th Percentile**: 9403.56
- **95th Percentile**: 16580.36
- **99th Percentile**: 38898.65

## Visualizations

The following visualizations are available in the 'evaluation_plots' directory:

1. **Actual vs Predicted**: Shows how well the predictions match actual values
2. **Residual Plot**: Shows if there are patterns in the errors
3. **Residual Distribution**: Shows the distribution of errors
4. **Q-Q Plot**: Shows if residuals follow a normal distribution
5. **Percentage Error Distribution**: Shows the distribution of percentage errors
6. **Error by Prediction Magnitude**: Shows if errors increase with prediction size

## Conclusion

The model shows good predictive performance with high R² value.
