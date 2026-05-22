# RFM Customer Segmentation Analysis

## Project Overview

This project focuses on customer segmentation using RFM (Recency, Frequency, Monetary) analysis. The notebook analyzes customer purchasing behavior to identify valuable customer groups, improve retention strategies, and support data-driven business decision-making.

Using transactional customer data, the project applies exploratory data analysis, feature engineering, scoring techniques, and segmentation logic to classify customers based on purchasing activity and value contribution.

This project is designed as a practical business analytics and customer intelligence exercise using Python data analysis libraries.

---

## Business Problem

Businesses need to understand customer behavior to improve:

* Customer retention
* Personalized marketing
* Revenue growth
* Loyalty strategies
* Sales targeting

RFM analysis helps organizations identify:

* Loyal customers
* High-value customers
* At-risk customers
* Inactive customers

This project transforms raw transaction data into actionable customer segmentation insights.

---

## What is RFM Analysis?

RFM stands for:

| Metric    | Meaning                                 |
| --------- | --------------------------------------- |
| Recency   | How recently a customer made a purchase |
| Frequency | How often a customer purchases          |
| Monetary  | How much money the customer spends      |

RFM analysis is widely used in:

* E-commerce
* Retail analytics
* CRM systems
* Marketing automation
* Customer lifecycle analysis

---

## Dataset Information

The dataset contains customer transaction-related information such as:

* Customer ID
* Invoice Number
* Purchase Date
* Quantity
* Product Information
* Unit Price
* Total Revenue

The data is used to calculate customer-level behavioral metrics.

---

## Project Objectives

The primary objectives of this project are:

* Clean and preprocess transactional data
* Calculate Recency, Frequency, and Monetary values
* Segment customers based on purchasing behavior
* Identify high-value and low-engagement customers
* Generate business-driven customer insights
* Visualize customer distribution patterns

---

## Technologies Used

### Programming Language

* Python 3

### Libraries

* pandas — data cleaning and aggregation
* numpy — numerical operations
* matplotlib — visualization
* seaborn — statistical charts
* scikit-learn — optional clustering and scaling

---

## Data Cleaning & Preprocessing

### Cleaning Operations

The notebook includes:

* Removing missing values
* Eliminating duplicate records
* Handling cancelled transactions
* Converting date columns to datetime format
* Creating total purchase amount columns

### Feature Engineering

Key engineered features include:

* Recency score
* Frequency count
* Monetary value
* RFM scoring
* Customer segment labels

---

## RFM Calculation Logic

### Recency

Measures the number of days since the customer’s most recent purchase.

### Frequency

Measures how frequently the customer makes purchases.

### Monetary

Measures the total amount spent by the customer.

---

## Customer Segmentation

### Example Customer Segments

The project may classify customers into groups such as:

| Segment             | Description                     |
| ------------------- | ------------------------------- |
| Champions           | Recent, frequent, high spenders |
| Loyal Customers     | Frequent repeat buyers          |
| Potential Loyalists | Customers with growth potential |
| At Risk             | Previously active but declining |
| Lost Customers      | Inactive customers              |
| Big Spenders        | High monetary contributors      |

---

## Exploratory Data Analysis (EDA)

### Customer Behavior Analysis

The notebook explores:

* Purchase frequency trends
* Spending distribution
* Customer activity timelines
* Revenue contribution patterns

### Segment Analysis

Analysis includes:

* Segment-wise customer counts
* Revenue by customer group
* High-value customer identification

---

## Visualizations Included

### Bar Charts

* Customer segment distribution
* Revenue contribution by segment

### Heatmaps

* RFM score relationships
* Correlation analysis

### Histograms

* Monetary value distribution
* Frequency distribution

### Pie Charts

* Customer category proportions
* Segment contribution percentages

---

## Business Insights Generated

The project helps identify:

* Most profitable customer groups
* Customers likely to churn
* High-frequency repeat buyers
* Revenue-driving customer segments
* Retention improvement opportunities

---

## Repository Structure

```bash id="w7n3vp"
rfm-customer-segmentation/
│
├── dataset/
│   └── customer_transactions.csv
│
├── notebooks/
│   └── RFM.IPYNB
│
├── images/
│   └── charts/
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

## Installation

### Clone Repository

```bash id="d8k4rt"
git clone https://github.com/your-username/rfm-customer-segmentation.git
```

### Navigate to Project Folder

```bash id="q1v7xn"
cd rfm-customer-segmentation
```

### Install Required Libraries

```bash id="m2x8zy"
pip install -r requirements.txt
```

---

## Running the Notebook

Launch Jupyter Notebook:

```bash id="y9n5kc"
jupyter notebook
```

Open:

```bash id="f4t2jq"
RFM.IPYNB
```

---

## Future Enhancements

Potential future improvements include:

* Interactive dashboard development
* Customer lifetime value prediction
* Automated marketing recommendations
* Clustering-based segmentation
* Streamlit deployment
* Real-time customer scoring systems

---

## Learning Outcomes

This project strengthens:

* Customer analytics understanding
* Business intelligence workflows
* Data preprocessing skills
* Customer segmentation techniques
* Exploratory data analysis
* Data storytelling and visualization

---

## References

* [Pandas Documentation](https://pandas.pydata.org/docs/?utm_source=chatgpt.com)
* [Scikit-learn Documentation](https://scikit-learn.org/stable/?utm_source=chatgpt.com)
* [Matplotlib Documentation](https://matplotlib.org/stable/contents.html?utm_source=chatgpt.com)
* [Seaborn Documentation](https://seaborn.pydata.org/?utm_source=chatgpt.com)

---

## License

This project is developed for educational, analytical, and portfolio-building purposes.
