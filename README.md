# credit-card-fraud-analytics

Credit card fraud detection system implemented using machine learning algorithms, including Isolation Forest, Local Outlier Factor, and Support Vector Machine, aimed at identifying fraudulent transactions within a highly imbalanced dataset through exploratory data analysis, principal component analysis and advanced anomaly detection techniques.

# Project Overview:
This analysis focuses on the most effiecient way to detect anomalies in credit card transactions.

# Define the problem:
1. Large number of transactions happen every single day. Hence, the model build must be fast enough to detect fraud transactions immediately.
2. Most of the transactions are non-fraudulent. Hence, it is hard to detect the fraudulent transactions.
3. Data availability. Since transaction related data are mostly private.
4. Model should work against the adaptive techniques used by the scammers.

# Dataset includes information about:
1. The dataset contains transactions that occurred on two consecutive days.
2. It contains only numerical input variables. 
3. Features V1, V2, … V28 are the principal components obtained with PCA due to confidentality issues.
4. The only features which have not been transformed with PCA are 'Time' and 'Amount'.
5. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset.
6. The feature 'Amount' is the transaction Amount.
7. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise. 

# Methods Applied:
1. Exploratory Data Analysis.
2. Data Preprocessing.
3. Modelling algorithms like Isolation Forest, Local Outlier Factor, Support Vector Machine.

# Data Source:
Kaggle
