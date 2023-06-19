Certainly! Here is a list of feature selection algorithms commonly used for time series data:

1. Autocorrelation: Measures the correlation between a time series and its lagged versions, helping identify relevant lags.

2. Mutual Information: Calculates the amount of information shared between each feature and the target variable, considering both linear and non-linear relationships.

3. Time Series Cross-Correlation: Measures the similarity between a time series and a lagged version of another time series, aiding in identifying relevant features.

4. Recursive Feature Elimination (RFE): Iteratively removes less important features and builds models on the remaining features to assess their impact, continuing until a desired number of features is achieved.

5. L1 Regularization (Lasso): Applies L1 regularization to penalize less important features, encouraging sparse solutions where irrelevant features have coefficients of zero.

6. Fast Fourier Transform (FFT): Transforms time domain data into the frequency domain, revealing the presence of specific frequencies and their importance.

7. Wavelet Transform: Decomposes a time series into different frequency components using wavelet analysis, allowing the identification of features at various scales.

8. Random Forest Importance: Utilizes a random forest algorithm to evaluate the importance of features based on their contribution to the model's performance.

9. Gradient Boosting Feature Importance: Similar to random forest importance, gradient boosting algorithms (e.g., XGBoost, LightGBM) provide feature importance measures based on their contribution to the boosting process.

10. Dynamic Time Warping (DTW): Measures the similarity between two time series by aligning them in the time domain, aiding in feature selection by identifying relevant subsequences.

These are some popular feature selection algorithms used in the context of time series data. It's worth noting that the suitability of each algorithm depends on the specific characteristics and requirements of your time series problem.