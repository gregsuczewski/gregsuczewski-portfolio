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
