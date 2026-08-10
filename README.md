# Causal Impact Estimation

## Project Overview

This project estimates the causal impact of California's Proposition 99 (1989) on cigarette consumption using the **Synthetic Control Method**. The analysis compares actual cigarette sales in California with a synthetic counterfactual created from other U.S. states.

## Dataset

The Proposition 99 dataset contains state-level annual observations from 1970 to 2000, with variables including cigarette sales, income, beer consumption, age distribution, and cigarette prices.

## What Was Done

* Cleaned and prepared the data
* Handled missing values using state-wise interpolation
* Performed exploratory analysis of cigarette consumption trends
* Compared California with control states before and after 1989
* Constructed a synthetic California as the counterfactual
* Estimated the causal effect of Proposition 99
* Visualized the actual vs. synthetic outcomes

## Libraries Used

* **Pandas** — data manipulation
* **NumPy** — numerical computation
* **Matplotlib** — data visualization
* **Scikit-learn** — preprocessing and modeling
