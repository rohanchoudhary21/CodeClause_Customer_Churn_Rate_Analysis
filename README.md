# Customer-Churn-Rate-Analysis

Customer Churn rate is defined as the measure of rate of customer leaving a group or a company directly or indirectly over a given period of time. Here, we have used Telco Customer Churn Rate dataset from kaggle.com to perform the analysis. Here is the [link](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/download?datasetVersionNumber=1) to download it.

Firstly, we did data cleaning to ensure that the data is accurate, complete, and consistent. We then performed data-preprocessing so that it can be easily analysed, for eg, we converted tenure column into multiple bins for analysis.

Next, We performed Exploratory Data Analysis(EDA) to explore and analyze the data to understand its characteristics, identify patterns, and uncover insights. We visualized the data using graphs and charts, and identified relationships of variables with Churn.

Finally, Model Builing was done. We fitted different ML models to get the best accuracy for our dataset and after trial and error we ended up getting one with the best accuracy. It was Support Vector Machine (kernel='rbf') in our case.
