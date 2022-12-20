# classifying-sales-calls

The goal of this project was to predict the outcomes of demo calls for a Software as a Service company. This project is focused on understanding what are the drivers for demo call qualifications and whether a robust predictive model is achievable. Two data sets are utilized (both internal and derived from the company's Redshift data warehouse) focused on leads and "intro calls" (demo calls). The data warehouse collects the data from Salesforce and processes it via ETL but still requires intense data cleansing and wrangling.  

Some of the questions the project seeks to answer include but are not limited to:

☑️ To determine if correlations exist between key sales indicators (account level demographics, leadership characteristics, etc) and qualification outcome.

☑️ To determine if there is a statistically significant difference between qualified and disqualified intro calls regarding key characteristics.

☑️ To create a machine learning model that allows us to predict whether an intro call will be qualified and understand the different drivers of qualification across models.


For this project I implemented a gradient boosted tree model (XGBoost) to classify qualification of sales demo calls in order to improve forecasting efforts. I attained ~80% accuracy & demonstrated the value of implementing machine learning to solve low-hanging fruit problems on the business side. This demonstration showcased the value of implementing machine learning to solving low-hanging fruit business problems.
