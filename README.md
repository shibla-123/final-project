# Predicting Agricultural Production Quantities Using Machine Learning
## OVERVIEW
##### This project focuses on analyzing and predicting agricultural production quantities for various commodities across different regions and years. Agricultural production data, encompassing categories such as crop production, livestock inventory, and aquatic products, is essential for understanding trends in food supply and supporting effective planning in the agriculture sector.

##### The dataset used in this project contains records of agricultural production, with columns indicating the geographical region, year, commodity category, specific commodity type, production quantity (captured in the "Amount" column), and the unit of measurement. The "Amount" column, which represents the quantity produced in various units (such as tons, head, and hectares), serves as the target variable for this analysis.

##### The main goal of this project is to build a predictive model that can estimate production quantities based on historical data. By experimenting with different machine learning models and tuning hyperparameters, this project aims to identify key patterns and influential factors in agricultural production. Insights gained from the model can be used to predict future production trends and support decision-making processes for stakeholders, including policymakers, farmers, and agribusinesses.

## OBJECTIVE
##### The objective of this project is to develop a predictive model for estimating the quantity of agricultural commodities, as represented by the "Amount" column, across various regions, years, and categories. Using machine learning techniques, the model aims to identify patterns and key factors that influence production volumes. This will provide insights into agricultural trends and support data-driven decision-making for stakeholders, such as policymakers, farmers, and supply chain managers.

## Data preprocessing
##### Handle missing values in the dataset.

###### • Removing outliers .

###### •categorical Encoding: Categorical features were encoded using label encoding.

###### • Data Splitting: The dataset was split into training and testing sets.
## EDA
## Feature selection
##### RandomForestRegressor: Used to identify important features.
## Model training
##### Linear Regression
##### Decision Tree Regressor
##### Random Forest Regressor
##### Gradient Boosting Regressor
##### adaBoost Regressor
## Hyper parameter tuning
## CONCLUSION
##### The project effectively demonstrates the end-to-end process of building a machine learning model to predict production quantities. The use of multiple models and thorough evaluation ensures that the best possible model is selected. The hyperparameter tuning further enhances the model’sperformance, making it robust and reliable for real-world applications.
