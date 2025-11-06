# Medallion Architecture — ETL Pipeline

## Overview
This project demonstrates an end-to-end **ETL data pipeline** built in **Python** using **pandas** and **PyArrow**, designed around the **Medallion Architecture** framework (Bronze → Silver → Gold).  
The pipeline processes Mario Kart–themed gameplay data, transforming raw files into clean, analytics-ready datasets.

## Project Structure
Medallion-Architecture/
│
├── bronze/ # Raw ingested data
├── silver/ # Cleaned & transformed data
├── gold/ # Aggregated analytics outputs
├── IS640_ETL_Report.pdf # Final report / documentation
└── Mario_ETL_Pipeline.ipynb # Jupyter notebook source

## Key Features
- Implements the **Bronze, Silver, and Gold** layered design for modular data processing  
- Stores all data in optimized **Parquet** format  
- Generates performance summaries including:
  - Team rankings  
  - Player statistics  
  - Vehicle usage patterns  
  - World difficulty visualizations  

## Tools Used
- Python 3.12  
- pandas, PyArrow, NumPy  
- Jupyter Notebook  

## Author
**Michael Sobnosky**  
[LinkedIn](https://www.linkedin.com/in/michael-sobnosky-238031260/) | [Portfolio](https://michaelsobnosky.github.io/Michael_Sobnosky_Portfolio/)

