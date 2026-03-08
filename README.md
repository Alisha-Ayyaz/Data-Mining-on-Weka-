# Data-Mining-on-Weka-
Project Description:
This repository contains a data mining project focused on exploring, preprocessing, and extracting association rules from a clinical heart disease dataset. The dataset consists of 1,025 instances and 14 attributes, including metrics like age, resting blood pressure, serum cholesterol, and maximum heart rate. Using WEKA, the project identifies hidden patterns and clinical risk factors associated with heart disease.
Key Project Phases:
.Data Exploration & Preprocessing:
The data was analyzed for statistical distribution, correlations, and quality issues like noise and outliers. Techniques applied to clean and prepare the data include equal-frequency discretization, Min-Max normalization, and binning-based data smoothing.
.Dimensionality Reduction (PCA): Principal Component Analysis (PCA) was implemented to eliminate redundancy and reduce dimensionality, successfully capturing the most critical features across 70%, 85%, and 95% variance thresholds.
.Association Rule Mining: The Apriori algorithm was utilized to discover strong clinical patterns. To ensure the reliability and clinical value of the rules, they were evaluated against multiple interestingness measures, including Confidence, Lift (Interest), Leverage, and Conviction.
