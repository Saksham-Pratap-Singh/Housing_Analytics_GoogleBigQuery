# 🏠 Housing Analytics: Google BigQuery & Power BI

### 🚀 Project Overview
This project performs an end-to-end analysis of housing market data to identify price trends, property characteristics, and key value drivers. The solution leverages **Google Cloud Platform (BigQuery)** for scalable data storage and querying, and **Power BI** for interactive visualization.

### 🛠 Tech Stack
* **Database & Cloud:** Google BigQuery
* **Query Language:** Standard SQL
* **Visualization:** Microsoft Power BI
* **Data Source:** Excel/CSV Flat files

### 📊 Project Workflow
1.  **Data Ingestion:** Raw housing data (`Housing Data.csv`) was loaded into Google BigQuery.
2.  **Data Processing (SQL):** * Performed data cleaning, standardization, and aggregation using SQL within the BigQuery console.
    * *Documentation:* See `GoogleBigQuery_Usage.pdf` for the query logic and environment setup.
3.  **Visualization:** * Connected Power BI to the processed data to build an interactive dashboard.
    * Created metrics for average housing prices, location-based analysis, and property feature correlations.
    * *Output:* See `Housing_Report.pbix` for the source file or `Housing_Dashboard_Images.pdf` for a quick preview.

### 📂 Repository Structure
| File | Description |
| :--- | :--- |
| **`Housing_Report.pbix`** | 📈 **Main Dashboard File**. Open with Power BI Desktop to view the interactive report. |
| **`GoogleBigQuery_Usage.pdf`** | ☁️ **SQL Documentation**. Contains screenshots and explanations of the BigQuery SQL workflow. |
| **`Housing_Dashboard_Images.pdf`** | 🖼️ **Dashboard Preview**. Static screenshots of the final Power BI report. |
| **`Housing Data.csv`** | 💾 Raw dataset used for analysis. |
| **`Housing+Data+Column+Definitions.xlsx`** | 📖 Data Dictionary defining the variables used. |

### 💡 Key Insights Generated
* **Price Analysis:** Identification of high-value regions and price distribution.
* **Property Features:** Correlation between property age, size, and market value.
* **Trend Visualization:** Visual representation of housing metrics across different segments.

---
*Created by [Saksham Pratap Singh](https://github.com/Saksham-Pratap-Singh)*
