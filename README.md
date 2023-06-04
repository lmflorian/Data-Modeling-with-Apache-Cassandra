**Data Modeling with Apache Cassandra**
------------------------------------------------------

This is the fist project for Data Engineering Nanodegree program from Udacity.  The principal goal is to put into practice the concepts of Data Modeling with Cassandra and ETL Pipeline with Python.

**Proyect Summary**

A startup named Sparkify has been collecting data on songs and user activity through their music streaming app. The analysis team at Sparkify wants to gain insights into the songs that users are listening to. However, the current data storage format is not conducive to easily querying and generating the desired results.  To address this issue, we are going to create in this project a NoSQL Apache Cassandra database. The purpose of this database is to enable the analysis team to run queries on the song play data and obtain the necessary answers.

**Content**

1.	[event_data](./event_data) is the directory of CSV files partitioned by date.
2.	[Project_1B_ Project_Template.ipynb](Project_1B_ Project_Template.ipynb) has the code for the ETL pipeline and data modeling

**Goals**

1.	Implement the logic  to iterate through each event file in event_data to process and create a new CSV file (event_datafile_new.csv) in Python with all the data

2.	Process the event_datafile_new.csv dataset to create a denormalized dataset

3.	Model the data tables keeping in mind the necessary queries to run

4.	Load the data into tables in Apache Cassandra and run the queries