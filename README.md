# Sparkify Project of Data Modelling with PostgreSQL
This project is from Udacity's Data Engineering Nanodegree program. This project builds an ETL pipeline with PostgreSQL. First, it creates the database and required tables. Then it reads data from the given files, transforms it and then populates in tables. The data modelling is done via star schema.

### Getting Started
- Download the project and unzip it or clone the project.


### Prerequisites
- Python 3.5+ --> Download from here https://www.python.org/downloads/
- Postgres --> Download from here https://www.postgresql.org/download/

### Project Structure
:page_with_curl: data/ <b>--></b> keep the data<br>
:page_with_curl: create_tables.py <b>--></b> python script to create database and tables <br>
:page_with_curl: etl.py <b>--></b> python script to read data in json format, transform it and then populate the tables <br>
:page_with_curl: sql_queries.py <b>--></b> python script to write SQL queries <br>

### Install
You need to install python dependencies. Open your terminal and execute:

```
pip install -r requirements.txt
```

### Executing and Setting Up
After the pre-requisites are satisfied:
In Terminal/CommandPromt:
Create the database and tables by running the following command:
```
python create_tables.py
```
Once the above ran successfully, populate the database by running below command:
```
python etl.py
```

### Data Modelling: Star Schema
We follow the structure present in the image for modelling the data.
![star](img/star.png)

### Authors
* **Rupali Sinha** - *Initial work*

