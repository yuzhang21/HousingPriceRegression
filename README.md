# HousingPriceRegression
## DS504 Project: Using Ensemble Regression Models to Predict Boston Housing Price

The data used in this project can be downloaded from the following website:

**Website Name:** *Analyze Boston, Property Assessment:* 

https://data.boston.gov/dataset/property-assessment

In this repository, there are 5 Jupyter Notebook files works for data processing:

### 1. S01_DataPreparation.ipynb

This scripts will read original data source in csv format and clean it up, save two intermediate files for later processing. 

Input file e.g. : *BH_BigDataset_2020.csv*

Output file e.g. :

*BH_BigDataset_2020.csv* for prepared data with categorical features

*BH_BigDataset_2020Full.csv* for prepared data with categorical features being converted using one-hot encoding

### 2. S02_FeatureSelection.ipynb

This scripts will read full processed data in csv format and conduct feature selection steps, save intermediate files for model fitting. 

Input file e.g. : *BH_BigDataset_2020Full.csv*

Output file e.g. : *BH_BigDataset_2020Reduced.csv* for feature reduced data with less features

### 3. S03_ModelTraining.ipynb

This scripts will read feature reduced processed data in csv format and conduct multiple model fittings. 

Input file e.g. : *BH_BigDataset_2020Reduced.csv*

### 4. S04_ModelTraining_CatBoost.ipynb

This scripts will read prepared data with categorical feature in csv format and conduct CatBoost model fitting. 

Input file e.g. : *BH_BigDataset_2020.csv*

### 5. S05_ModelTraining_Spark_MLlib.ipynb

This scripts will read feature reduced processed data in csv format or libsvm format and conduct two models fitting in MLlib. 

Input file e.g. : *BH_BigDataset_2020Reduced.csv* or *BH_BigDataset_2020Reduced_libsvm.data*

