# Online-Payment-Fraud-Detection- Project Overview
The digital age brought with it a trend of online payments. This led to the mass adoption of Cashless transactions; with instant electronic transfers/payments resulting in massive time savings and convenience. However, the increase in electronic transactions also came with a substantial increase in online fraudulent transactions.

The Case Study is of a multinational financial services group, that offers retail and investment banking, pension management, asset management and payments services, headquartered in London, UK.

The purpose of this project is to predict if an online transaction processed by the Bank is fraudulent or not, given the available data. This prediction would result in early detection of fraudulent online transactions and the deployment of necessary corrective actions to prevent loss of Funds.

## Resources
* Data Source: The Data of transaction records obtained from the Bank is in a csv file containing 1,048,575 records. 
* Python Version: 3.9.12
* Packages: pandas, numpy, sklearn, matplotlib, seaborn

## Exploratory Data Analysis (EDA)
I looked at the distribution of data for the various variables (using Univariate and Multivariate Analysis). Below are a few highlights from the EDA Performed:

![2022-12-29 (1)](https://user-images.githubusercontent.com/117505903/209954390-c5dcdcd5-2e2f-4714-abca-d3f2a6d8812a.png)

![2022-12-29 (4)](https://user-images.githubusercontent.com/117505903/209954401-644cfe2a-e30f-4b39-abda-7763d112dce1.png)

![2022-12-29 (3)](https://user-images.githubusercontent.com/117505903/209954418-bb393664-ed0a-4711-8723-00619903382b.png)


## Data cleaning 
* Features with strong correlations were dropped
* Categorical variables were encoded using dummy encoding
* Some irrelevant (non-encoded) categorical variables were dropped 

## Model Building
* The data was split into train and tests sets with a test size of 30%.
* Four (4) models were used: Logistic Regression, Random Forest, K-Nearest Neighbors and Decision Tree.

## Model Performance
* The Random Forest Classifier outperformed the other approaches in terms of Accuracy, Precision, Recall and F1-Score. It's Classification report and Confusion Matrix is shown below:

![Confusion Matrix Resized](https://user-images.githubusercontent.com/117505903/209953524-e20a1961-9d38-4aaf-9d6c-ac2d77220ba4.png)

## Feature Importance
* This was carried out for the Random Forest Classifier and the top 5 Features in determining whether a transaction is legitimate or not were identified.

## Deployment
* Deployment is not within the scope of this project.






