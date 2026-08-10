# Causal Impact on Cigarette Sales

## Objective

Evaluate the impact of Proposition 99, introduced in California in 1989, on cigarette sales using the **Synthetic Control Method (SCM)**.

## Dataset

* Years: **1970–2000**
* Treated unit: **California**
* Outcome: **Cigarette sales per capita**
* Control units: Other U.S. states

## Method

**Synthetic California** was created as a weighted combination of control states to estimate California's cigarette sales without Proposition 99.

The treatment effect was calculated as:

**Actual California − Synthetic California**

## Main Results

* **Pre-treatment RMSPE:** 1.66
* **Average treatment effect:** −19.51
* **California RMSPE ratio:** 12.44
* **Placebo p-value:** 0.103

Actual cigarette sales declined significantly more than Synthetic California after 1989.

## Control-State Weights

The largest weights were assigned to:

* **Utah:** 39.39%
* **Montana:** 23.18%
* **Nevada:** 20.49%
* **Connecticut:** 10.91%
* **New Hampshire:** 4.54%
* **Colorado:** 1.48%

## Conclusion

The results suggest that Proposition 99 contributed to a reduction in cigarette sales in California. However, the **placebo p-value** of 0.103 means that the effect was not statistically significant at the 5% level.
