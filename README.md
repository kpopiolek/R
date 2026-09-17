This repository contains my academic reports made in R Studio.

# Linear Regression Analysis (linear_regression.pdf)

## Tools and Technologies

* **Libraries**: *tidyverse*, *ggplot2*, *dplyr*, *knitr*.

## Scope of Work

* **Baseline Model**: Estimating the structural dependencies using the **Ordinary Least Squares (OLS)** method on the 2014 baseline dataset.
* **Alternative Estimation Techniques**: Validating the baseline parameters through manual implementation of the **Method of Moments (MM)** and **Maximum Likelihood Estimation (MLE)**.
* **Robustness and Simulation Analysis**: Evaluating parameter stability under spatial anomalies using non-parametric **Bootstrap resampling**, followed by a **Monte Carlo simulation** to confirm the unbiasedness of the estimators.
* **Out-of-Sample Evaluation**: Verifying the model's predictive accuracy on the 2015 validation dataset using **MAE**, **RMSE**, and **MAPE** error metrics.
* **Dynamic Modeling**: Estimating a **First Differences (FD)** model to isolate short-term causal effects and eliminate time-invariant regional heterogeneity.

# Iris Species Classification Using Naive Bayes (naive_bayes_classification.pdf)

## Tools and Technologies

* **Libraries**: *tidyverse*, *e1071*, *ggplot2*, *patchwork*, *knitr*, *stringr*.

## Scope of Work

* **Data Preprocessing**: Verifying data integrity, removing class name prefixes, transforming data types into factors, and splitting the dataset into training (80%) and testing (20%) sets.
* **Assumption Verification**: Performing the **Shapiro-Wilk test** to check the normal distribution of the variables.
* **Modeling and Classification**: Training the **Naive Bayes algorithm** on all available features, achieving an overall prediction accuracy of 93.3%.
* **Feature Selection**: Using visual analysis (box-plots) to identify the most significant **explanatory variables** (**petal length** and **petal width**). Retraining the model with reduced dimensionality maintained the 93.3% accuracy while optimizing computational resources.

# RMS Titanic Statistical Data Analysis (titanic.pdf)

## Tools and Technologies

* **Libraries**: *tidyverse*, *dplyr*, *ggplot2*, *knitr*.

## Scope of Work

* **Data Preprocessing**: Filtering observations, correcting spelling errors, and imputing missing age values using median and passenger honorific titles.
* **Descriptive Statistics**: Calculating the overall survival rate using relative frequency.
* **Univariate and Multivariate Analysis**: Evaluating the impact of individual variables and their interactions on the evacuation outcome.
* **Historical Verification**: Verifying the actual application of the unofficial "women and children first" evacuation protocol in the context of wealth barriers.
