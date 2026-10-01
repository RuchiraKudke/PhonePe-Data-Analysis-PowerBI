# 📊 PhonePe Transaction Analysis Dashboard

## 📌 Project Overview

This project is an interactive **PhonePe Transaction Analysis Dashboard** developed using **Microsoft Power BI**.

The project focuses on analyzing transaction and user data to understand transaction patterns, payment performance, user activity, and trends over time. Power Query was used for data preparation, while DAX was used to create measures and KPIs for the dashboard.

The project was developed as a hands-on Power BI learning project using the referenced YouTube tutorials as a guide for data preparation, data modeling, DAX development, and dashboard design.

---

## 🎯 Objectives

The main objectives of this project are:

- Analyze PhonePe transaction data using Power BI.
- Understand transaction trends over time.
- Analyze transaction and payment performance.
- Explore user-related transaction activity.
- Create meaningful KPIs using DAX.
- Perform Month-over-Month (MoM) and Year-over-Year (YoY) analysis.
- Build an interactive and easy-to-understand dashboard.
- Present data-driven insights through visualizations.

---

## 🗂️ Dataset

The dataset used in this project was obtained from the resource link provided in the description of the referenced YouTube tutorial.

The data consists of separate transaction and user tables.

### Source Tables

| Table | Description | Records |
|---|---|---:|
| `All_Transactions` | Transaction-level data | 300,000 |
| `All_Users` | User-level information | 1,07,658 |

In addition to the source tables, two tables were created within Power BI:

| Table | Purpose |
|---|---|
| `Date_Table` | Created for date and time-based analysis |
| `Measures` | Created to organize DAX measures |

The `Date_Table` and `Measures` tables are Power BI-created tables and therefore are not included as source dataset records.

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop**
- **Power Query** – Data cleaning and transformation
- **DAX** – Measures and calculations
- **CSV / Excel** – Dataset
- **GitHub** – Project documentation and version control

---

## 🔄 Data Cleaning & Transformation

The source data was imported into Power BI and prepared for analysis using **Power Query**.

The data preparation process included:

- Importing the transaction and user tables.
- Reviewing the structure of the dataset.
- Checking and preparing column data types.
- Transforming the data where required.
- Preparing the source tables for data modeling and analysis.

The cleaned data was then loaded into the Power BI data model.

---

## 🔗 Data Modeling

A data model was created in Power BI to connect the transaction, user, and date information required for analysis.

The `Date_Table` was created separately to support time-based calculations and analysis.

A dedicated `Measures` table was also created to organize the DAX calculations used throughout the dashboard.

The data model enables transaction and user information to be analyzed together and supports time-based calculations such as MoM and YoY analysis.

---

## 🧮 DAX Measures

DAX measures were created to calculate the key metrics required for the dashboard.

The measures were organized in a dedicated `Measures` table.

The DAX calculations were used for:

- Transaction-related KPIs
- Transaction amount analysis
- User activity analysis
- Payment status analysis
- Month-over-Month (MoM) analysis
- Year-over-Year (YoY) analysis

These measures were used across the dashboard to provide dynamic results based on selected filters and slicers.

---

## 📊 KPI Analysis

Key Performance Indicators were created to provide a quick overview of important transaction and user metrics.

The KPI cards allow users to understand the overall performance of the data at a glance.

The KPIs are dynamically connected to the Power BI data model and respond to the applied filters and slicers.

---

## 📅 Time-Based Analysis

A dedicated `Date_Table` was created to perform time-based analysis.

DAX time-intelligence calculations were used to analyze changes in transaction performance across different periods.

The dashboard includes:

- **Month-over-Month (MoM) Analysis**
- **Year-over-Year (YoY) Analysis**
- Transaction trends over time

These calculations help identify changes and patterns in transaction activity.

---

## 📈 Dashboard

The final Power BI dashboard combines KPIs, charts, filters, and interactive visualizations to present the analyzed data in a clear format.

### Dashboard Features

- KPI Cards
- Transaction Analysis
- User Analysis
- Time-based Trends
- Interactive Slicers
- Dynamic DAX Measures
- MoM and YoY Analysis
- Interactive Visualizations

### Dashboard Preview

<img width="1227" height="687" alt="Screenshot 2026-10-02 000836" src="https://github.com/user-attachments/assets/923414fe-51c3-4b17-88d6-8a069282425f" />

---

## 💡 Key Insights

The dashboard can be used to identify:

- Patterns in transaction activity.
- Changes in transaction performance over time.
- User-related transaction trends.
- Payment status patterns.
- Period-wise changes using MoM and YoY analysis.

The specific insights obtained from the dashboard are based on the selected filters and the underlying transaction and user data.

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Data cleaning and transformation using Power Query.
- Building relationships between Power BI tables.
- Creating a dedicated Date Table.
- Creating and organizing DAX measures.
- Developing KPIs.
- Performing MoM and YoY analysis.
- Designing interactive Power BI dashboards.
- Presenting data-driven insights visually.

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open `PhonePe_PowerBI_Dashboard.pbix` using **Power BI Desktop**.
3. If required, update the dataset/file path.
4. Refresh the data.
5. Use the available slicers and filters to explore the dashboard.

---

## 📖 References

### YouTube Tutorials

1. **DataCliq – PhonePe Data Analysis Project in Power BI | Business Insights, DAX, KPI Dashboard & Resume Project – Part 1**  
   https://youtu.be/YMBw-zJgwdU

2. **DataCliq – PhonePe Power BI Dashboard Design | Resume Project – Part 2**  
   https://youtu.be/IHiWmCJI2

---

## 👩‍💻 Author

**Ruchira Kudke**

MCA – Artificial Intelligence & Data Science

Interested in **Data Analytics, Power BI, Python, SQL, and Data Science**.
