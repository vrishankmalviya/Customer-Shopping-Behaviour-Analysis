# 🛒 Customer Shopping Behavior Analysis

**End-to-End Data Analysis using Python, SQL, and Power BI**

## 📌 Project Overview

This project analyzes customer shopping behavior using transactional retail data to uncover insights into **spending patterns, customer segments, product performance, and subscription behavior**.

The goal is to help business stakeholders make **data-driven decisions** related to marketing strategy, customer engagement, pricing, and product positioning.

The project follows a complete **analytics lifecycle**:

* Data cleaning and preparation (Python)
* Business-focused analysis (SQL)
* Interactive dashboarding (Power BI)
* Actionable business recommendations

---

## 🎯 Business Problem

A retail company observed changes in purchasing behavior across:

* Customer demographics
* Product categories
* Discounts and subscriptions
* Online vs. offline channels

The management team wanted to understand:

> **How can consumer shopping data be leveraged to identify trends, improve customer engagement, and optimize marketing and product strategies?**

---

## 📊 Dataset Summary

* **Rows:** 3,900 transactions
* **Columns:** 18 features

### Key Features

* **Customer Demographics:** Age, Gender, Location, Subscription Status
* **Purchase Details:** Item, Category, Purchase Amount, Season, Size, Color
* **Behavioral Metrics:** Discounts, Previous Purchases, Purchase Frequency
* **Feedback:** Review Ratings
* **Logistics:** Shipping Type

⚠️ Missing values were present in the *Review Rating* column and were handled during preprocessing.

---

## 🧪 Project Workflow

### 1️⃣ Data Preparation & EDA (Python)

* Loaded and explored the dataset using **pandas**
* Handled missing values using **median imputation by product category**
* Standardized column names for consistency
* Performed feature engineering:

  * Age group segmentation
  * Purchase frequency derivation
* Validated data consistency and removed redundant fields
* Exported cleaned data to a PostgreSQL database for analysis

---

### 2️⃣ Business Analysis (SQL – PostgreSQL)

Performed structured SQL analysis to answer key business questions:

* Revenue contribution by **gender**
* Spending behavior of **discount users**
* **Top-rated products** by average review score
* Comparison of **standard vs. express shipping**
* Spending patterns of **subscribers vs. non-subscribers**
* Identification of **discount-dependent products**
* **Customer segmentation** into New, Returning, and Loyal users
* Top products within each category
* Relationship between repeat purchases and subscriptions
* Revenue distribution across **age groups**

---

### 3️⃣ Data Visualization (Power BI)

Built an interactive Power BI dashboard showcasing:

* Total customers
* Average purchase value
* Revenue by category
* Sales and revenue by age group
* Subscription distribution
* Shipping type preferences

The dashboard allows stakeholders to filter and explore insights dynamically.

---

## 📈 Key Insights

* Loyal and repeat customers contribute the majority of revenue
* Subscription customers show higher long-term value
* Certain products are highly **discount-sensitive**, impacting margins
* Younger and middle-aged customer groups drive the highest revenue
* Express shipping users show slightly higher average purchase values

---

## 💡 Business Recommendations

* Promote **subscription benefits** to increase customer lifetime value
* Introduce **loyalty programs** for repeat buyers
* Optimize **discount strategies** for margin-sensitive products
* Highlight **top-rated and best-selling products** in marketing campaigns
* Focus targeted promotions on **high-revenue age groups**

---

## 🛠️ Tech Stack

* **Python:** pandas, NumPy
* **Database:** PostgreSQL
* **Visualization:** Power BI
* **Tools:** SQL, Jupyter Notebook

---

## 📂 Project Structure

```
Customer-Shopping-Behavior-Analysis/
│
├── data/                  # Raw and cleaned datasets
├── notebooks/             # Python notebooks for EDA and preprocessing
├── sql/                   # SQL queries for business analysis
├── powerbi/               # Power BI dashboard file
├── report/                # Project report and findings
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies
```

---

## 🚀 How to Run the Project

1. Clone the repository

   ```bash
   git clone <repository-url>
   cd Customer-Shopping-Behavior-Analysis
   ```
2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Python notebooks for data cleaning and EDA
4. Execute SQL queries in PostgreSQL
5. Open the Power BI file to explore the dashboard

---

## 📌 Use Cases

* Retail & E-commerce analytics
* Customer segmentation & loyalty analysis
* Sales and revenue optimization
* Marketing and pricing strategy

---

## 📬 Contact

If you’d like to discuss this project or explore collaboration opportunities, feel free to connect.

---


