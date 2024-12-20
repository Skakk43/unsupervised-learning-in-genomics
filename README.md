<header>

# Project Description

</header>

This project examines the statistical methods used to analyze high dimensional genomic data.

## What are high dimensional data?

High dimensional data are data in which the number of features, _p_, are close to or larger than the number of observations, _n_. These data are becoming more common in recent years due to ability to collect, store, and compute more data.

## Why is dealing with high dimensional data challenging?

1. One challenge to analyzing high dimensional data is visualing the variables while conveying the message effectively.
2. Another challenge is the high correlations between explanatory variables during regression models. Because there are many features, samples are more likely to be highly correlated. High correlations can obscure the contribution of each variable, and resulting in increased risk of overfitting the data.

## What statistical methods are used to analyze high dimensional data?

> 1. __Regression with numerous outcomes__ refers to situations in which there are many variables of a similar kind (expression values for many genes, methylation levels for many sites in the genome) and when one is interested in assessing whether these variables are associated with a specific covariate of interest, such as experimental condition or age. In this case, multiple univariate regression models (one per each outcome, using the covariate of interest as predictor) could be fitted independently. In the context of high-dimensional molecular data, a typical example are differential gene expression analyses. We will explore this type of analysis in the Regression with many outcomes episode.
> 2. __Regularisation__ (also known as regularised regression or penalised regression) is typically used to fit regression models when there is a single outcome variable or interest but the number of potential predictors is large, e.g. there are more predictors than observations. Regularisation can help to prevent overfitting and may be used to identify a small subset of predictors that are associated with the outcome of interest. For example, regularised regression has been often used when building epigenetic clocks, where methylation values across several thousands of genomic sites are used to predict chronological age. We will explore this in more detail in the Regularised regression episode.
> 3. __Dimensionality reduction__ is commonly used on high-dimensional datasets for data exploration or as a preprocessing step prior to other downstream analyses. For instance, a low-dimensional visualisation of a gene expression dataset may be used to inform quality control steps (e.g. are there any anomalous samples?). This course contains two episodes that explore dimensionality reduction techniques: Principal component analysis and Factor analysis.
> 4. __Clustering__ methods can be used to identify potential grouping patterns within a dataset. A popular example is the identification of distinct cell types through clustering cells with similar gene expression patterns. The K-means episode will explore a specific method to perform clustering analysis.

<footer>

Reference:
[High dimensional statistics with R] (https://carpentries-incubator.github.io/high-dimensional-stats-r)

</footer>
