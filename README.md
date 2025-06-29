# DiSTect

## High-dimensional Bayesian Model for Disease-Specific Gene Detection in Spatial Transcriptomics

Identifying disease-indicative genes is critical for deciphering disease mechanisms and continues to attract significant interest. Spatial transcriptomics offers unprecedented insights for
the detection of disease-specific genes by enabling within-tissue contrasts. However, this new
technology poses challenges for conventional statistical models developed for RNA-seq, as
these models often neglect the spatial organization of tissue spots. In this article, we propose
a Bayesian shrinkage model to characterize the relationship between high-dimensional gene
expressions and the disease status of tissue spots, incorporating spatial correlation among
these spots through autoregressive terms. Our model adopts a hierarchical structure to
accommodate for the missing data within tissues and is further extended to facilitate the
analysis of multiple correlated samples. To ensure the model’s applicability to datasets of
varying sizes, we carry out two computational frameworks for Bayesian parameter estimation, tailored to both small and large sample scenarios. 

## Install the package
To install the R package, first download the file named "BayModDSGD_0.0.0.9000.tar.gz". Then, execute the following command in the R environment to complete the installation: "install.packages("path/to/BayModDSGD_0.0.0.9000.tar.gz", repos = NULL, type = "source")".



## Tutorial

A R Markdown of the tutorial is accessible from: [https://qihuangzhang.github.io/software/DiSTect_tutorial](https://qihuangzhang.github.io/software/DiSTect_tutorial).

## Data

The dataset about HER2-positive breast is accessible from https://github.com/almaan/her2st.
