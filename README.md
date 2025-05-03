# **End-to-End Azure Data Pipeline: Netflix Project**

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
  
- **Power BI**:
  - Power BI files that visualize Netflix data trends, including content distribution by country, genre, and user ratings.

## **Setup & Installation**
To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
