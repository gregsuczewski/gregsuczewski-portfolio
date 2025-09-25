# gregsuczewski-portfolio

Portfolio of Data Analysis and Data Science in Python

Bootstrap Analysis of Dark Hydrogen Recombination Coefficient
-------------------------------------------------------------

File: interaction_cutoff.ipynb

This notebook performs bootstrap resampling to estimate the mean and 95% confidence intervals 
for dark hydrogen recombination coefficients. The coefficient data files were computed via Monte Carlo 
integration over a truncated power series. The goal of this notebook is to verify convergence 
as a function of the number of terms retained in the power series and to report reliable 95% 
confidence intervals for the converged recombination coefficients.

Input:
- Text files containing recombination coefficient data.

Output:
- Histogram plots of resampled means with 95% confidence intervals.


Simple Linear Regression for Housing Price Predictions
-------------------------------------------------------------

File: real_estate_pricing.ipynb

This notebook demonstrates the application of a simple linear regression model to predict housing prices.
It includes preprocessing steps, such as feature and label transformations, to better capture extreme price
values and enhance model performance. The notebook evaluates the model using R² and visualizes predictions
versus actual prices.

Input:
- Housing dataset in text format (sourced from Kaggle).

Output:
- Performance metrics and visualizations.


Predicting Temperature using an LSTM Model
-------------------------------------------------------------

File: lstm.ipynb

This notebook demonstrates the application of a Long Short-Term Memory (LSTM) model to predict tomorrow’s 
temperature based on historical weather data. It includes preprocessing steps such as handling missing values,
scaling features, and removing erroneous data. The model is trained with a Mean Squared Error (MSE) loss function,
and performance is reported using both MSE and Mean Absolute Error (MAE). Early stopping with a validation set 
is employed to prevent overfitting. Predicted temperatures are visualized against actual values to highlight model
accuracy and lag effects.

Input:
- Weather dataset in text format (sourced from Kaggle).

Output:
- Performance metrics and visualizations comparing predicted vs. actual temperatures.
