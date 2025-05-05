# <img src="https://github.com/Roaa-Talat/End-to-End-Real-Time-Data-Pipeline-on-Azure-Netflix-Project/blob/main/Screenshot/Netflix.png" width="30" /> **etflix: End-to-End Azure Data Pipeline Project**

## **Table of Contents**
- [Project Overview](#project-overview)
- [Architecture](#architecture)
- [Key Technologies Used](#key-technologies-used)
- [Project Structure](#project-structure)
- [Power BI Dashboard](#power-bi-dashboard)

## **Project Overview**
This project demonstrates the end-to-end implementation of a **real-time data pipeline** using **Azure Data Factory**, **Databricks**, and **Power BI**. The project processes the **Netflix dataset**, integrating raw data, applying data transformations, and enabling real-time analytics using Apache Spark and Databricks Delta Live Tables.

## **Architecture**
The architecture diagram below showcases the entire flow of the end-to-end data pipeline, starting from data ingestion to real-time processing and visualization.

![Architecture Diagram](https://github.com/Roaa-Talat/End-to-End-Real-Time-Data-Pipeline-on-Azure-Netflix-Project/blob/main/Architecture.png)

## **Key Technologies Used**
- **Azure Data Factory**: For orchestrating ETL pipelines.
- **Azure Databricks**: For data processing and Spark-based transformations.
- **PySpark**: For handling large-scale data processing.
- **Databricks Delta Live Tables**: For managing data pipelines.
- **Power BI**: For creating an interactive dashboard.

## **Project Structure**
- **Notebooks**: 
  - *1_Autoloader.ipynb*: Real-time data ingestion using Autoloader.
  - *2-Silver.ipynb*: Data transformation and cleaning in the silver layer.
  - *3-LookupNotebook.ipynb*: Lookup operations for enriching data.
  - *4-Silver.ipynb*: Additional transformations and data filtering.
  - *5-LookupNotebook.ipynb*: Logic for setting and retrieving task values using Databricks widgets and jobs.
  - *6-FalseNotebook.ipynb*: Retrieves the task value from the previous task.
  - *8-DataCleaning.ipynb*: Data cleaning and preprocessing for Netflix dataset.
  - *7-DLTNotebook.ipynb*: Delta Live Tables pipeline setup.
  
- **Data**:
  - *netflix_cast.csv*: Cast information for Netflix titles.
  - *netflix_category.csv*: Genre categories for movies and shows.
  - *netflix_countries.csv*: Country data for content availability.
  - *netflix_titles.csv*: Original Netflix dataset with metadata.
  
- **Power BI**:
  - Power BI files visualizing Netflix data.
  
## **Power BI Dashboard**
The Power BI dashboard presents a variety of visualizations, enabling users to interact with and explore different aspects of the Netflix content data. By leveraging interactive elements, users can dive deeper into various dimensions of the dataset, exploring everything from content characteristics to distribution patterns across different attributes.
- **Power BI**:
  - Power BI reports that provide a comprehensive overview of the Netflix dataset, enabling users to explore different dimensions of the data. These reports help visualize patterns, relationships, and key attributes within the dataset, offering a holistic view of the information for better understanding and decision-making.

![Page 1 of Power BI](https://github.com/Roaa-Talat/End-to-End-Real-Time-Data-Pipeline-on-Azure-Netflix-Project/blob/main/PowerBI/Page1.jpg)
![Page 2 of Power BI](https://github.com/Roaa-Talat/End-to-End-Real-Time-Data-Pipeline-on-Azure-Netflix-Project/blob/main/PowerBI/Page2.jpg)
