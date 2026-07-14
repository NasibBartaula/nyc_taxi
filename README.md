# NYC Taxi ETL Pipeline 🚖

An end-to-end Data Engineering pipeline designed to extract, transform, and load (ETL) New York City taxi trip data. This project processes raw trip records to clean the dataset, handle missing values, and extract key insights such as high-fare zones, peak travel hours, and trip duration trends.

## 🚀 Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Jupyter Notebook
* **Version Control:** Git & GitHub

## ⚙️ ETL Process
1. **Extraction:** Ingesting NYC taxi raw dataset files (CSV/Parquet format).
2. **Transformation:** 
   * Cleaning missing or corrupted values.
   * Formatting datetime columns.
   * Creating derived columns (e.g., trip duration, speed, peak hours).
   * Aggregating data by pickup locations and payment types.
3. **Loading:** Exporting the clean, structured data into optimized formats for downstream analysis or visualization.

## 📂 Repository Structure
* `notebooks/` - Jupyter notebooks containing step-by-step data exploration and ETL prototyping.
* `data/` - (Excluded from GitHub via `.gitignore` due to file size limits) Placeholder folder for raw and processed datasets.
