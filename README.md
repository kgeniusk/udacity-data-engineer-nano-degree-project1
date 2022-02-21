# Project: Data Modeling with Postgres

## Overview
The goal of the project is to create a database for song play analysis. 
The database consists of the following tables.

* fact table
  * songplays
* dimension tables
  * songs
  * artists
  * time
  * users

<img src="erd.png" width="600"/>

## How to run the scripts

```bash
# 1. create tables (exisiting tables will be dropped at fisrt)
python create_tables.py

# 2. insert data to tables
python etl.py
```

## List of files
* data: contains the sample data
* create_tables.py: drops existing tables and create new tables
* etl.py: read sample data and insert into the database
* sql_queries.py: SQL statements for creating, inserting and selecting tables


