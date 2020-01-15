# pyspark-project
In this project, the Walmart stock data is explored and analyzed using apache spark.
Apache spark is preferred by many organizations for large scale data processing and analytics. It can perform ETL, analytics, querying, machine learning and graph processing. 
The platform used in this project is Databricks, since Databricks is a well-crafted platform that avoids complexities of big data and machine learning. The apache spark API supports many languages such as R, python, java, scala etc. The data is analyzed using pyspark imported in python.

Exploration of data:
1.	The data is imported and the information of data is collected 
2.	The dataset is checked for null values
3.	A separate column consisting of high-volume ratio is created
4.	Following information are found out:
I.	 Day that had peak high in price
II.	Average of close
III.	Minimum Volume
IV.	Maximum volume
V.	The number of days when the close was lower than 60
VI.	Percentage of the time, high was greater than 80 dollars
VII.	Pearson correlation of high and low
VIII.	Max high per year
IX.	Max high per month
X.	Distinct months
5.  Built a Linear regression Model
