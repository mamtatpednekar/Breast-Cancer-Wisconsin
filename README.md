# Breast-Cancer-Wisconsin


Objective
To build a meaningful cancer classification model on the Wisconsin dataset.
2- Dataset
We use Breast Cancer Wisconsin (Diagnostic) Dataset. The data can 
be downloaded from the UC Irvine Machine Learning Repository.
The first dataset looks at the predictor classes:
• Malignant or 
• Benign breast mass 
The features include:
• Sample ID (code number) 
• Clump thickness 
• Uniformity of cell size 
• Uniformity of cell shape 
• Marginal adhesion 
• Single epithelial cell size 
• Number of bare nuclei 
• Bland chromatin 
• Number of normal nuclei 
• Mitosis 
• Classes, i.e. diagnosis 
3- Tasks
a. Data Analysis and missing data analysis. 
i. Is there missing data? 
ii. Can we afford to remove data points? 
iii. Do we use imputation (and introduce additional uncertainty)?
b. Features Engineering
i. Features distribution plot (for all features) 
ii. Imputation
c. Generate a heap map plot for all features
i. Univariate Selection in Scikit
 SelectKBest class from Scikit can be used to choose n best features.
d. Principal Component Analysis (PCA)
Run PCA and plot the PC1 and PC2 for two categories
e. Training, Validation, Testing
f. Machine learning models. 
i. Decision Tree base model
ii. Random Forest
iii. SVM
