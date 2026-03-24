Lab 4: Data Quality Assessment & Preprocessing

Dataset: insurance.csv

Overview:

This lab demonstrates preprocessing steps on the insurance dataset, including missing value handling, outlier detection, normalization, and PCA.

Tasks Completed
 1. Data Quality Check

 • Verified data types; numerical and categorical features are correct.
 • Checked for duplicates → 1 duplicate removed.
 • Checked for missing values → none found.
 
 2. Missing Value Strategy
 • Demonstrated Mean and Median imputation as examples, although no missing values were present.

 3. Outlier Detection (IQR Method)
 • Detected and removed outliers in bmi and charges to improve data quality.

 4. Normalization
 • Applied Min-Max scaling → values scaled between 0 and 1.
 • Applied Z-score standardization → mean ≈ 0, std ≈ 1.
 
 5. Principal Component Analysis (PCA)
 • Checked correlations between numerical features.
 • Applied PCA → extracted PC1 and PC2 capturing most of the variance.

Conclusion
The dataset is now cleaned, normalized, and ready for machine learning modeling or further analysis.
