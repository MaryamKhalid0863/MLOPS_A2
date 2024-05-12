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
