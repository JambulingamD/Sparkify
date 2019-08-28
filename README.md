# Sparkify Project
Udacity Data Science Nanodegree project.

### Overview:
Sparkify is a music streaming service like spotify. Churing is a common occurance in service 
industry and churning leads to losing customers and thus the revenue. Being a service, 
Sparkify is also subjected to churning. The company want to idenfiy the customers who are
likely to churn, so that they can provide target promotions to retain the customers. Sparkify
already captured the customer activity and wants to use data science to predict while the customers
are about to churn based on their activities.

### Process:
Binary classification model can be used to address this requirement. Here are the steps:
1. Load large datasets into Spark and manipulate them using Spark SQL and Spark Dataframes
2. Clean the dataset
3. Use the machine learning APIs within Spark ML to build the models
4. Train and tune the model
5. Uses seaborn to visualize the findings
6. Runs the model in Apache Spark to publish the findings!

Check the [blog](http://www.google.com) for further details.

Look at the [Jupyter Notebook](https://github.com/JambulingamD/Sparkify/blob/master/Sparkify.ipynb) for the python script.

### Datascience libraries used:
pandas
numpy
seaborn
matplotlib
datetime
pyspark

### Conclusion:
1. Sparkify has a high churn rate
2. Random Forest Claiisifier model can predict the customers who are about to churn with a very high accuracy
2. This ia very good opportunity to increase the revenue of the company by coming up with the right promotion plan to keep the customers who are about to churn.