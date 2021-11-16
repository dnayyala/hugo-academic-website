---
title: PREPR
subtitle: Pre-pivoting root based test statistic for comparing mean vectors of
  two populations in high dimensional data sets.
date: 2020-11-02T04:48:14.337Z
summary: Package available at https://github.com/dnayyala/prepr
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
Testing equality of mean vectors is a very commonly used criterion when comparing two multivariate random variables. Traditional tests such as Hotelling’s $T^2$ become either unusable or output small power when the number of variables is greater than the combined sample size. This package implements a new test procedure developed using pre-pivoting and Edgeworth expansion for testing the equality of two population mean vectors in the "large p, small n" setting. An illustration of the test procedure is provided and the method is applied to analyze the colorectal cancer gene expression data set from Alon et al. (1999).