# University Analytics System

This repository contains the implementation of an university analytics system that utilizes Informatica PowerCenter as an ETL tool to integrate data from various sources into a Data Warehouse with a Star Schema. The system is designed to handle Slowly Changing Dimensions (Type I and Type II).

## Description

The primary objective of this project is to create an efficient and reliable data integration system that ensures the accurate and timely transfer of data from source systems to the Data Warehouse. The key features of this system include:

- **Informatica PowerCenter**: Used as an ETL (Extract, Transform, Load) tool for data integration.
- **Data Warehouse**: The target data repository is designed with a Star Schema to optimize query performance and data retrieval.
- **Slowly Changing Dimensions (SCD)**:
  - **Type I**: Overwrites old data with new data.
  - **Type II**: Tracks historical data by creating multiple records.

## Features

### Informatica PowerCenter
Informatica PowerCenter is utilized to perform the ETL processes, which include:

- **Extraction**: Extracting data from various source systems.
- **Transformation**: Cleaning, transforming, and enriching the data to ensure consistency and quality.
- **Loading**: Loading the transformed data into the Data Warehouse.

### Star Schema
The Data Warehouse is structured using a Star Schema, which consists of:

- **Fact Tables**: Store quantitative data for analysis.
- **Dimension Tables**: Contain descriptive attributes related to the fact data, facilitating efficient data retrieval.

### Slowly Changing Dimensions (SCD)
The system handles Slowly Changing Dimensions to manage changes in dimension data effectively:

- **Type I**: Updates existing records with new information, overwriting old data.
- **Type II**: Creates new records for changes, preserving historical data for analysis.

## Installation

To set up the project, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/Deb-Code-Hub/Analytics-System.git
