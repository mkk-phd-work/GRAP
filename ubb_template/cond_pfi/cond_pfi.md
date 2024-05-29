# Conditional Permutation Feature Importance (PFI) for multi-series data

## Introduction

Permutation Feature Importance (PFI) is a model-agnostic method to estimate the importance of features in a predictive model. The idea is to measure the decrease in model performance when the values of a feature are randomly permuted. The larger the decrease in performance, the more important the feature is. PFI is a powerful tool to understand the importance of features in a model and to identify features that are not important.

A major limitation is that permutation can generate feature combinations that are not realistic. For example, if we permute the values of a feature, we may generate a combination of feature values that is not observed in the data. This can lead to an overestimation of the importance of the feature.

For multi-series (independent) forecasting for example the lagged values usually have high importance but when permuted values from different series are combined. Also some exogenous variables can appear on one series but not on the other. This can lead to an overestimation of the importance of the exogenous variable.


## Conditional subgroups approach

 
{cite:ps}`christophmolnar2020` https://link.springer.com/article/10.1007/s10618-022-00901-9




## Conditional Permutation (Feature) Importance (CPI)

Conditional feature importance for mixed data
https://link.springer.com/article/10.1007/s10182-023-00477-9

Conditional permutation importance revisited
https://link.springer.com/article/10.1186/s12859-020-03622-2?fromPaywallRec=false



## References

```{bibliography}
:filter: docname in docnames
```