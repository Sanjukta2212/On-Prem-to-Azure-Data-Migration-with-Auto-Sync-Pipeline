# AdventureWorks Cloud Migration and Analysis Pipeline

## Overview

This repository details the AdventureWorks database migration journey from an on-premises SQL Server Management Studio (SSMS) setup to a cloud-based solution using Microsoft Azure. The migration is accompanied by dynamic and insightful visualizations powered by Power BI. A robust pipeline ensures seamless data synchronization between the source database and Power BI reports.

## Major Tools and Services Used

### Data Ingestion:
- **Azure Data Factory:** Establishes a connection to the on-prem SQL database and orchestrates data transfer to the cloud.

### Data Storage:
- **Azure Data Lake Storage Gen2:** Centralized data storage solution leveraging Lakehouse architecture for optimal data management.

### Data Transformation:
- **Azure Databricks:** Transforms raw data into a structured and analysis-ready format.
- **Azure Synapse Analytics:** Integrates various services for comprehensive data warehousing and analytics.

### Data Visualization:
- **Power BI:** Creates interactive and meaningful visualizations reflecting processed data.

### Security and Compliance:
- **Azure Active Directory:** Manages secure access to project services.
- **Azure Key Vault:** Secures application secrets and keys within the Azure cloud environment.

## Pipeline Architecture

The pipeline is designed to adapt to changes in the source database. It automatically detects modifications in the SSMS source and processes them through subsequent stages of storage, transformation, and visualization in Power BI.

## Repository Content

This repository contains comprehensive documentation, sample codes, and configurations necessary to replicate the cloud migration and data analysis setup. Follow the provided guidance to create a similar environment tailored to your data needs.
