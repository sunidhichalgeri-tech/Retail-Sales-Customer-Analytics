# Retail-Sales-Customer-Analytics
Retail sales analysis using Python, Pandas, Matplotlib, and RFM customer segmentation.
# 📊 Retail Sales and Customer Analytics

## 📌 Project Overview

This project focuses on analyzing retail transaction data using Python to discover sales trends, identify top-performing products, understand customer purchasing behavior, and generate meaningful business insights.

Data analysis and visualization techniques are used to help understand sales performance and customer behavior.

## 🎯 Objectives

- Analyze monthly revenue trends.
- Identify top-performing products.
- Analyze customer purchasing patterns.
- Compare revenue across countries.
- Perform RFM customer segmentation.
- Calculate average order value.
- Create visualizations to communicate findings.
- Generate actionable business insights.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📈 Analysis Performed

### 1. Monthly Revenue Analysis
Analyzed monthly revenue trends to identify the highest- and lowest-revenue months.

### 2. Product Analysis
Identified products generating the highest revenue and products sold in the greatest quantities.

### 3. Customer Analysis
Examined customer purchasing behavior and identified customers contributing the most revenue.

### 4. Country-Wise Sales Analysis
Compared revenue across countries to identify the strongest markets.

### 5. RFM Customer Segmentation
Applied RFM analysis to understand customer behavior using:

- **Recency:** How recently a customer purchased.
- **Frequency:** Number of distinct invoices associated with a customer.
- **Monetary:** Total recorded revenue associated with a customer.

Customers were classified into four preliminary segments:

- High Value
- Loyal Customers
- At Risk
- Others

### 6. Business Metrics
Calculated total revenue, unique invoice count, and average revenue per invoice.

### 7. Data Quality Analysis
Checked missing values, duplicate records, and unusual quantity and price values.

## 🔍 Key Findings

The analysis produced the following results:

| Metric | Result |
|---|---:|
| Total Recorded Revenue | 10,642,110.80 |
| Unique Invoices | 19,960 |
| Average Revenue per Invoice | 533.17 |
| Highest Revenue Month | November 2011 |
| Highest Revenue Country | United Kingdom |
| Top Product by Recorded Revenue | DOTCOM POSTAGE |
| Highest Revenue-Contributing Customer Segment | High Value |

### Customer Segment Revenue Contribution

| Customer Segment | Revenue Contribution |
|---|---:|
| High Value | 49.32% |
| Others | 22.53% |
| Loyal Customers | 20.91% |
| At Risk | 7.24% |

*These percentages represent revenue attributed to identified customers under the current segmentation rules.*

## 📊 Visualizations

The project includes visualizations for:

- Monthly revenue trends
- Top products by revenue
- Top products by quantity sold
- Top customers by revenue
- Revenue by country
- Customer segmentation
- Revenue by customer segment
- Revenue contribution by customer segment
- Monthly order trends
- Average order value

## 💡 Business Insights

- High-value customers contribute a substantial share of identified-customer revenue.
- The United Kingdom is the leading market by recorded revenue.
- Revenue varies considerably across months.
- Product revenue and sales quantity can be compared to understand product performance.
- RFM segmentation helps identify customers for further retention analysis.

## ⚙️ Installation and Usage

### Prerequisites

- Python 3.x
- Jupyter Notebook

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Run the Project

1. Clone or download this repository.
2. Open the project directory.
3. Launch Jupyter Notebook.
4. Open the analysis notebook.
5. Ensure the required dataset is available at the file path specified in the notebook.
6. Run the cells sequentially to reproduce the analysis.

## 📁 Project Structure

```text
Retail-Sales-Customer-Analytics/
│
├── README.md
├── retail_sales_analysis.ipynb
├── retail_sales_cleaned.csv
└── customer_rfm_analysis.csv
```

*The filenames above are examples. Replace them with the actual filenames in your repository.*

## ⚠️ Limitations

- Some transaction records have missing CustomerIDs.
- Customer-level analysis excludes transactions without identifiable customers.
- Customer segments are based on preliminary rule-based classifications.
- Revenue results depend on the dataset's cleaning and filtering rules.
- Cancellations, returns, and unusual transactions should be validated before making definitive business decisions.

## 🔮 Future Improvements

- Develop an interactive sales dashboard.
- Improve customer segmentation.
- Analyze seasonal sales patterns in greater detail.
- Investigate customer retention and repeat purchases.
- Add more advanced statistical analysis.
- Automate report generation.

## 📄 Conclusion

This project demonstrates how Python-based data analysis can be used to explore retail sales performance, understand customer purchasing behavior, and identify business opportunities.

The findings provide a foundation for further analysis and data-driven decision-making.
