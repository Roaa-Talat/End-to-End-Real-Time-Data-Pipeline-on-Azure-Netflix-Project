# **End-to-End Azure Data Pipeline: Netflix Project**

## **Table of Contents**
- [Project Overview](#project-overview)
- [Key Technologies Used](#key-technologies-used)
- [Project Structure](#project-structure)
- [Architecture](#architecture)
- [Power BI Dashboard](#power-bi-dashboard)

## **Project Overview**
This project demonstrates the end-to-end implementation of a **real-time data pipeline** using **Azure Data Factory**, **Databricks**, and **Power BI**. The project processes the **Netflix dataset**, integrating raw data, applying data transformations, and enabling real-time analytics using Apache Spark and Databricks Delta Live Tables.

## **Key Technologies Used**
- **Azure Data Factory**: For orchestrating ETL pipelines.
- **Azure Databricks**: For data processing and Spark-based transformations.
- **PySpark**: For handling large-scale data processing.
- **Databricks Delta Live Tables**: For managing data pipelines.
- **Power BI**: For creating an interactive dashboard.
- **Apache Spark Streaming**: For real-time data processing.

## **Project Structure**
- **Notebooks**: 
  - *1_Autoloader.ipynb*: Real-time data ingestion using Autoloader.
  - *2-Silver.ipynb*: Data transformation and cleaning in the silver layer.
  - *3-LookupNotebook.ipynb*: Lookup operations for enriching data.
  - *4-Silver.ipynb*: Additional transformations and data filtering.
  - *8-DataCleaning.ipynb*: Data cleaning and preprocessing for Netflix dataset.
  - *7-DLTNotebook.ipynb*: Delta Live Tables pipeline setup.
  - *... (and more notebooks depending on your pipeline)*
  
- **Data**:
  - *netflix_cast.csv*: Cast information for Netflix titles.
  - *netflix_category.csv*: Genre categories for movies and shows.
  - *netflix_countries.csv*: Country data for content availability.
  - *netflix_titles.csv*: Original Netflix dataset with metadata.
  - *netflix_titles_cleaned.csv*: Cleaned version of the dataset ready for analysis.
  
- **Power BI**:
  - Power BI files that visualize Netflix data trends, including content distribution by country, genre, and user ratings.

## **Architecture**
The architecture diagram below showcases the entire flow of the end-to-end data pipeline, starting from data ingestion to real-time processing and visualization.

![Architecture Diagram](https://github.com/Roaa-Talat/End-to-End-Real-Time-Data-Pipeline-on-Azure-Netflix-Project/blob/main/Architecture.png)

## **Power BI Dashboard**
The Power BI dashboard provides insightful visualizations of Netflix content trends, such as content distribution by genre and country, along with user ratings and more.

Here are a couple of screenshots from the Power BI reports:

- ![Page 1 of Power BI](https://github.com/Roaa-Talat/End-to-End-Real-Time-Data-Pipeline-on-Azure-Netflix-Project/blob/main/PowerBI/Page1.jpg)
- ![Page 2 of Power BI](https://github.com/Roaa-Talat/End-to-End-Real-Time-Data-Pipeline-on-Azure-Netflix-Project/blob/main/PowerBI/Page2.jpg)
