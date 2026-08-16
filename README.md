# Online Retail Sales Analytics

A Python-based data analytics project analyzing retail transactions to uncover revenue trends, sales-volume patterns, and top-performing products.

## 📌 Project Overview

This project follows an end-to-end data analytics workflow:

**Raw Data → Data Understanding → Data Cleaning → EDA → Visualization → Business Insights**

The analysis was performed using Python, Pandas, and Matplotlib.

## 📊 Key Highlights

- **541,909** original transaction records
- **401,604** records after data cleaning
- **£8.28M** recorded revenue in the cleaned dataset
- **November 2011** had the highest complete-month revenue
- **REGENCY CAKESTAND 3 TIER** was the highest revenue-generating product description
- Revenue and sales volume showed a strong upward pattern from **September to November 2011**

> **Note:** December 2011 is an incomplete month because the dataset ends on December 9, so it should not be directly compared with complete months.

## 🛠️ Tools & Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Microsoft Excel

## 📂 Project Structure

```text
online-retail-sales-analytics/
│
├── Report/
│   └── Online_Retail_Sales_Analytics_Report.pdf
│
├── data/
│   ├── Online_Retail.xlsx
│   └── online_retail_cleaned.xlsx
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_exploratory_analysis.ipynb
│   └── 04_matplotlib_visualization.ipynb
│
└── README.md
```

## 📓 Notebooks

| Notebook | Purpose |
|---|---|
| `01_data_understanding.ipynb` | Initial dataset inspection and data-quality assessment |
| `02_data_cleaning.ipynb` | Data cleaning, validation, duplicate removal, and preparation |
| `03_exploratory_analysis.ipynb` | Revenue, sales volume, and product-level analysis |
| `04_matplotlib_visualization.ipynb` | Visualization of the main analytical findings |

## 📈 Visualizations

The project includes visual analysis of:

- Monthly revenue trends
- Monthly quantity sold
- Top revenue-generating products
- Revenue vs. sales volume

## 🎯 Project Objective

The objective was to transform raw retail transaction data into meaningful business insights through a structured and reproducible data analytics workflow.

## 📄 Detailed Documentation

A complete project report is available in the `Report` folder.

The report covers:

- Dataset overview
- Data-quality assessment
- Data-cleaning methodology
- Exploratory analysis
- Visualizations
- Key findings
- Business interpretation
- Limitations
- Future scope
- Conclusion

## 💡 Key Insights

- November 2011 recorded the highest revenue among the complete months in the dataset.
- Revenue and sales quantity increased together during the September–November period.
- `REGENCY CAKESTAND 3 TIER` generated the highest revenue among the analyzed product descriptions.
- The dataset contains both normal sales transactions and non-standard records such as cancellations, returns, and accounting adjustments, which required cleaning before analysis.
- December 2011 represents only a partial month and was therefore treated carefully during interpretation.

## 🚀 Future Scope

The analysis can be extended with:

- Customer segmentation
- RFM analysis
- Customer lifetime value analysis
- Country-level revenue analysis
- Repeat customer analysis
- Product return analysis
- Seasonal analysis
- Interactive Power BI dashboards
- Advanced statistical analysis

## 👤 Author

**Ankan Mondal**
