# Medallion Architecture (Mario) — ETL Pipeline

### 🏁 Project Overview
This project demonstrates an end-to-end **ETL data pipeline** built in **Python** using **pandas** and **PyArrow**, designed around the **Medallion Architecture** (Bronze → Silver → Gold).  
The dataset is based on *Mario Kart–themed gameplay data*, and the pipeline transforms raw data into clean, analytics-ready layers, ending with visual summaries and insights.

### 🧱 Architecture Overview
| Layer | Description | Files |
|:------|:-------------|:------|
| 🥉 **Bronze** | Raw data ingestion and initial processing | [Bronze_Mario.ipynb](https://github.com/MichaelSobnosky/Medallion-Architecture/blob/main/Bronze_Mario.ipynb) |
| 🥈 **Silver** | Data cleaning, transformation, and integration | [Silver.ipynb](https://github.com/MichaelSobnosky/Medallion-Architecture/blob/main/Silver.ipynb) |
| 🥇 **Gold** | Final analytics layer with reports and visual summaries | [IS640_ETL_Report.html](https://github.com/MichaelSobnosky/Medallion-Architecture/blob/main/IS640_ETL_Report.html) |

### 📊 Key Features
- Implements the **Medallion Architecture** to separate data ingestion, cleaning, and analytics
- Uses **pandas** and **PyArrow** for data transformation and Parquet integration
- Produces summary insights including:
  - Player and team performance analytics  
  - Vehicle usage breakdowns  
  - World difficulty comparisons  

### 🧠 Tools & Libraries
Python • pandas • PyArrow • NumPy • Jupyter Notebook

---

**Author:** [Michael Sobnosky](https://www.linkedin.com/in/michael-sobnosky-238031260/)  
📂 [View Portfolio](https://michaelsobnosky.github.io/Michael_Sobnosky_Portfolio/)

## Author
**Michael Sobnosky**  
[LinkedIn](https://www.linkedin.com/in/michael-sobnosky-238031260/) | [Portfolio](https://michaelsobnosky.github.io/Michael_Sobnosky_Portfolio/)

