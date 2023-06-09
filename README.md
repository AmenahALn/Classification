## Classification
This repository presents a study on classifying data based on their characteristics using Latent Class, K-means, and Two-Step clustering methods. The main objective of the study is to evaluate the performance of the Latent Class and compare its results with K-means and Two-Step methods. Additionally, the optimal category for building the model is determined.
#### 1. Key Findings:
* Five categories were initially compared, but the results were fairly similar. Thus, three categories were chosen, and it was found that the optimal category is two for all methods.
* The Average Silhouette index was used to evaluate the performance of the three methods, with Latent Class showing the best results, followed by Two-Step and K-means.
* The study concluded that Latent Class provides a better fit for the data compared to Two-Step and K-means, indicating a higher degree of similarity within its clusters.
* We present the model L2 statistic, which measures the association between variables after estimating the model. The p-value criterion is used to determine the number of classes, with Model 2 (2-classes model) selected as the best model based on its p-value and number of parameters.
* We provide R2 values, indicating the variance explained by the two cluster models for each indicator. 
* The analysis in this project relied on the combined usage of MATLAB and R for data processing, modeling, and statistical computations.
* The following figures illustrate the impact of variables. Additionally, a Uni-plot is included to validate the distribution of data across the two classes.
<div style="display: flex;">
  <img src="https://github.com/AmenahALn/Risk-based-Modeling-and-Prediction/blob/main/return.JPG" alt="First Image" style="width: 40%;">
  <img src="https://github.com/AmenahALn/Risk-based-Modeling-and-Prediction/blob/main/return_2.JPG" alt="Second Image" style="width: 40%;">
</div>