---
layout: post
title:  "Portfolio of projects"
date:   2017-04-19 14:07:43 +0200
---
Xhangolli, K. 2017. *“Testing for time-invariant unobserved correlation in Seemingly Unrelated Regression (SUR) with three dimensions”*  
We propose through fixed effect estimation, a necessary test for time invariant unobserved effects correlation in a SUR model with 3 dimensions (such as panel data with multiple dependent variables). The test implementation in R consist of extending panel tests of `plm` package. First 3D SUR are transformed into 2D SUR by proper vectorization and Kronecker product operations applied through efficient matrix operation packages `SparaseM` and `bdsmatrix`. After residuals of the transformation are computed through `plm` panel tests, the covariance structure of the residuals is tested for non-correlation with bootstrap. 

Xhangolli, K. 2017. *“Predicting admission to public higher education institutions programs with a naïve classifier and RShiny web application”*. Code on [Github](https://github.com/kreshnikxhangolli/matura-albania-Lite)  
A naïve percentile classifier is computed based on students’ inputted grades and scores of past winners. Scores of past winners were retrieved from irregular Excel tables using functions `tidyverse` multipackage. A data construct consisting of a five-levels deep list is saved and called as an `RDS` object for efficient percentile computation. The classifier is visualized by partially filled distribution graphs which are created by manipulating the `ribbon` geom of `ggplot2`.

Xhangolli, K. 2017. *“Parametric estimation of treatment effects with time-varying qualification in panel data and repeated cross-sections”*. Files on [Github](https://github.com/kreshnikxhangolli/parametric-treatment-effects) and [Research Gate](https://www.researchgate.net/publication/315831369_Parametric_estimation_of_treatment_effects_with_time-varying_qualification_in_panel_data_and_repeated_cross-sections)  
In this theoretical work we provide an unrestricted linear model for identifying treatment effects with time-varying qualification with panel data and repeated cross-sections. This model enables fixed and random effects estimation of treatment effects; the latter has not been considered before. In addition we identify new scenarios and respective sufficient conditions for treatment effect estimation in such settings.

Xhangolli, K. and Egbert, H. 2017. *“Measuring treatment effects of Albanian 2009 Healthcare Reform”*.  
Using the theoretical results of Xhangolli (2017) we estimate treatment effects using repeated cross-section data. Efficient R scripts read selected variables while matching for different variable naming, different unit of measurement (household vs. individual) and different file location (each survey module is stored in a different file).
