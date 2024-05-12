# MLOps Assignment 2: Airflow Automation

## Introduction
In this assignment, we focus on implementing an automated data pipeline using Apache Airflow, a platform for programmatically authoring, scheduling, and monitoring workflows. The project integrates advanced practices in MLOps to automate the cycle of data extraction, transformation, and storage, complemented by robust version control mechanisms. This hands-on project helps in understanding and applying practical aspects of MLOps to real-world data workflows, leveraging popular tools and technologies to manage and automate tasks effectively.

## Overview
This project involves implementing Apache Airflow to automate the data pipeline processes for extracting, transforming, and storing data with version control using DVC. The primary data sources for this project are [Dawn](https://www.dawn.com/) and [BBC](https://www.bbc.com/).

## Objective
The main goal is to use Apache Airflow to automate:
- **Data Extraction**: Extract data from the landing pages of Dawn and BBC.
- **Data Transformation**: Clean and format the extracted text data.
- **Data Storage**: Upload the processed data to Google Drive.
- **Version Control**: Use DVC to manage data versions effectively.

## Prerequisites
- Python 3.8
- Apache Airflow
- Data Version Control (DVC)
- Git

## Implementation
### Setting Up the Environment
- **Create a Virtual Environment**:
  Using a virtual environment is crucial to manage dependencies and versions specific to this project without affecting the global Python environment.
  ```bash
  python -m venv venv
  ```
 - **Activate the Virtual Environment**:
  ```bash
  venv\Scripts\activate
  ```
 - **Install Dependencies**:
  Ensure all required packages are installed by using a requirements file:
  ```bash
  pip install -r requirements.txt
  ```
### Configuring Apache Airflow
  - **Airflow Initialization**:
  Initialize the database used by Airflow to track task instances and workflows:

  ```bash
  airflow db init
  ```
- **Creating the DAG**:
  Develop a Directed Acyclic Graph (DAG) in Airflow to define the workflow of tasks including extraction, transformation, and loading (ETL).


### Data Extraction
 - **Web Scraping**: Implement Python scripts using requests and BeautifulSoup to scrape data from specified URLs.
 - **Error Handling**: Implement robust error handling to manage and log issues during the scraping process.
   
### Data Transformation
 - **Cleaning Data**: Use regular expressions and string operations to clean and format the extracted data.
 - **Transformation Logic**: Detail the specific transformations applied to the data to prepare it for storage.
   
### Data Storage and Version Control
 - **Storing in Google Drive**: Configure and utilize the Google Drive API to store the transformed data files.

### Conclusion
  Wrap up with a brief summary of what was achieved and any lessons learned during the project implementation. Discuss potential improvements or next steps for the project.

