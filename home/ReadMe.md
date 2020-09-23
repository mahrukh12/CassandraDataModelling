Project:
        Data Modeling with Cassandra

Introduction:

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. There is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app. My role is to create an Apache Cassandra database which can create queries on song play data to answer the questions.

Project Overview:

The purpose of this project is to create an Apache Cassandra database for a ficticious startup called Sparkify to query on song play data. The raw data is in a directory of CSV files, and we will build a ETL pipeline to transform the raw data into the Apache Cassandra database.

Datasets:

For this project, you'll be working with one dataset: event_data. The directory of CSV files partitioned by date. Here are examples of filepaths to two files in the dataset: event_data/2018-11-08-events.csv event_data/2018-11-09-events.csv

Project Template:

The project template includes one Jupyter Notebook file, in which: 

    • you will process the event_datafile_new.csv dataset to create a denormalized dataset
    • you will model the data tables keeping in mind the queries you need to run 
    • you have been provided queries that you will need to model your data tables for
    • you will load the data into tables you create in Apache Cassandra and run your queries

Project Steps:

Below are steps you can follow to complete each component of this project.

Modelling your NoSQL Database or Apache Cassandra Database:
       
       • Design tables to answer the queries outlined in the project template
       • Write Apache Cassandra CREATE KEYSPACE and SET KEYSPACE statements
       • Develop your CREATE statement for each of the tables to address each question
       •  Load the data with INSERT statement for each of the tables
       • Include IF NOT EXISTS clauses in your CREATE statements to create tables only if the tables do not already m  exist. We recommend you also include DROP TABLE statement for each table, this way you can run drop and create tables whenever you want to reset your database and test your ETL pipeline
       •  Test by running the proper select statements with the correct WHERE clause

Build ETL Pipeline:

    Start with the raw csv data files as described in Dataset
    For each row of the csv data, insert the data in the appropriate column as described in Schema
    Perform the Select query as described in Queries

Files:

Project_1B_Project_Template.ipynb: 

This was template file provided to fill in the details and write the python script

Event_datafile_new.csv: 

This is the final combination of all the files which are in the folder event_data

Event_Data Folder: 

Each event file is present separately, so all the files would be combined into one into event_datafile_new.csv

Build Instructions

Run each portion of Project_1B_Project_Template.ipynb.

Author

    Mahrukh Malik