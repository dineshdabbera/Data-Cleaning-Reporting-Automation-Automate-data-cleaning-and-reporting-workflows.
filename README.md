Cafe Sales Data Cleaning & Reporting Automation
This project focuses on automating data cleaning and reporting workflows using Python and Power BI.

Project Overview
Raw sales data often contains missing values, duplicates, and inconsistencies. This project demonstrates how to clean such data and generate meaningful insights automatically.
Key Features
- Automated data cleaning (handling missing values, duplicates, inconsistent data)
- Data transformation and preprocessing using Python
- Automated reporting and summary generation
- Visualization-ready cleaned dataset

Tools & Technologies
- Python (Pandas, NumPy)
- Matplotlib
- Power BI
- CSV / Excel

Workflow
1. Load raw dataset
2. Clean data (handle missing values, remove duplicates)
3. Convert data types
4. Recalculate incorrect values
5. Generate summaries and insights
6. Export cleaned dataset

Key Insights
- Identified top-selling items based on revenue
- Analyzed sales distribution across locations
- Observed trends in payment methods

Project Structure
cafe-sales-analysis/
│
├── data/
│   ├── dirty_cafe_sales.csv
│   ├── cleaned_cafe_sales.csv
│
├── notebook/
│   └── data_cleaning.ipynb
│
├── dashboard/
│   └── powerbi_dashboard.pbix
│
├── README.md

Future Improvements
- Add machine learning for sales prediction
- Build a web dashboard using Streamlit
- Automate report generation (PDF/Excel)

