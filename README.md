# Data Modeling with Cassandra Project 

## Disclaimer
This is Udacity's Data Engineering non-relational data modeling project solution. The data, project template and part of this readme files were taken from the course's material. 
## Introduction

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

They'd like a data engineer to create an Apache Cassandra database which can create queries on song play data to answer the questions, and wish to bring you on the project. Your role is to create a database for this analysis. You'll be able to test your database by running queries given to you by the analytics team from Sparkify to create the results.

## Datasets
For this project, you'll be working with one dataset: event_data. The directory of CSV files is partitioned by date.

## Project Template
A project template that takes care of all the imports and provides a structure for ETL pipeline needed to process this data.
## Prerequisites
You will need python3, pandas, numpy and a cassandra instance to run the notebook in this project. 
## Specification

Design and implement the database tables, insert statements and verify the insertion of the data to enable those three queries examples: 

1. Give me the artist, song title and song's length in the music app history that was heard during sessionId = 338, and itemInSession = 4
2. Give me only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182
3. Give me every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own'¶
