# Financial Regulation case study

Case Study: Financial Regulation
Domain: Banking
All financial institutions have been introduced to a new financial regulation that will consider the impact of possible future events when calculating their risk exposure.
For this change, all financial trading services will have to source data from far more data sources including both trade and risk data, which means large amounts of data
that have not historically been required for accounting.The data is of trading index listings for each trading day.

Goal:
To adhere to the regulation a leading trading service provider has decided to create a new repository (Big Data) and a multi-facet platform that can cater to these models.
As part of the R&D team, you are required to execute a POC exercise to maintain a master data model.

Steps
1. Test the spark environment by executing the spark’s HdfsTest.scala using SBT
2. Analyze the behavior of spark application on Spark web UI
3. Transfer the sample dataset from RDBMS to HDFS
4. Validate the loaded data by comparing the statistics of data both in source and HDFS
5. Create a new directory EQ in HDFS and transfer the data where series is EQ
6. Set total trades which are less than 500 to 0 and transfer only updated rows
