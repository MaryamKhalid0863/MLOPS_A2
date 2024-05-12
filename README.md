# WebScrapping-Apache-Airflow
# *MLOps Assignment 2: Airflow Automation*

## *Overview*
This project involves implementing Apache Airflow to automate the data pipeline processes for extracting, transforming, and storing data with version control using DVC. The primary data sources for this project are [Dawn](https://www.dawn.com/) and [BBC](https://www.bbc.com/).

## *Objective*
The main goal is to use Apache Airflow to automate:
- *Data Extraction*: Extract data from the landing pages of Dawn and BBC.
- *Data Transformation*: Clean and format the extracted text data.
- *Data Storage*: Upload the processed data to Google Drive.
- *Version Control*: Use DVC to manage data versions effectively.

## *Prerequisites*
- Python 3.x
- Apache Airflow
- Data Version Control (DVC)
- Git

## *Installation*

### Apache Airflow
1. *Install Airflow via pip*:
   ```bash
   pip install apache-airflow
