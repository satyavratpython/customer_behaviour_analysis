# customer_behaviour_analysis
data analytics project showcasing customer behavior analysis using python, sql and power BI

# Customer Shopping Behavior Analysis

## Overview

This project focuses on analyzing customer shopping behavior using transactional data to generate meaningful business insights. The objective is to understand customer segments, spending patterns, product performance, and subscription behavior through a complete analytics pipeline including Python, SQL, Power BI, reporting, and presentation.

The project demonstrates an end-to-end data analytics workflow suitable for real-world business intelligence and decision-making use cases.

---

## Dataset

**Source:** Transactional customer purchase dataset
**Size:** 3,900 rows × 18 columns

### Key Data Fields

* **Customer Info:** Age, Gender, Location, Subscription Status
* **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color
* **Behavioral Data:** Discount Applied, Promo Code Used, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type

### Data Quality

* Missing values identified in the `Review Rating` column
* Column names standardized for consistency
* Data types cleaned and validated

---

## Tools & Technologies

* **Python:** Pandas, NumPy, Matplotlib, Seaborn
* **Databases:** MySQL
* **BI Tool:** Power BI
* **Reporting:** Structured business report (PDF)
* **Presentation:** Gamma (PPT generation)

---

## Project Steps

### 1. Data Loading (Python)

* Loaded dataset using Pandas
* Performed initial inspection using `.info()` and `.describe()`

### 2. Exploratory Data Analysis (EDA)

* Statistical summaries
* Distribution analysis
* Category-wise and segment-wise exploration
* Pattern identification in spending and behavior

### 3. Data Cleaning & Feature Engineering

* Missing value treatment using median imputation (Review Ratings)
* Column renaming using snake_case
* Feature creation:

  * `age_group`
  * `purchase_frequency_days`
* Redundancy checks and column optimization

### 4. SQL Analysis ( MySQL )

Business-focused SQL queries were executed to analyze:

* Revenue by gender
* High-spending discount users
* Top-rated products
* Shipping type comparison
* Subscriber vs non-subscriber behavior
* Discount dependency by product
* Customer segmentation (New / Returning / Loyal)
* Top products per category
* Repeat buyers and subscription correlation
* Revenue by age group

### 5. Dashboard (Power BI)

An interactive dashboard was built to visualize:

* Revenue trends
* Customer segments
* Product performance
* Subscription impact
* Discount and shipping insights

### 6. Reporting

* Business insights documented in a structured analytical report
* Clear visual storytelling and insight explanation

### 7. Presentation

* Final insights presented using a professional PPT created in **Gamma**

---

## Dashboard

The Power BI dashboard provides:

* Interactive filters
* KPI indicators
* Segment-wise analysis
* Product and category performance
* Customer behavior insights

---

## Results & Insights

* Identified high-value customer segments
* Analyzed impact of discounts on revenue
* Evaluated subscription-based spending behavior
* Discovered top-performing products and categories
* Mapped revenue contribution by age groups

---

## Business Recommendations

* Strengthen subscription-based offers
* Build loyalty programs for repeat buyers
* Optimize discount strategies
* Promote high-rated and high-performing products
* Apply targeted marketing for high-revenue segments

---

## How to Run the Project

### Python Analysis

```bash
pip install pandas numpy matplotlib seaborn psycopg2
```

```python
python analysis.py
```

### SQL

* Import cleaned dataset into:

  * PostgreSQL / MySQL / SQL Server
* Run provided SQL scripts for business analysis

### Power BI

* Connect Power BI to the database
* Load processed tables
* Build dashboard using provided model

### Reporting

* Use generated insights for business report

### Presentation

* Use Gamma to create professional PPT using final insights

---

## Project Value

This project demonstrates:

* End-to-end data analytics pipeline
* Real-world business analysis approach
* Strong integration of Python, SQL, BI, and reporting


