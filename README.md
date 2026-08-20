# Tamil Nadu Elections 2021–2026
## 📊 **Power BI Data Analytics Dashboard**

<p align="center">

<img src="https://img.shields.io/badge/Power%20BI-Dashboard-yellow?style=for-the-badge&logo=powerbi" />
<img src="https://img.shields.io/badge/DAX-Analytics-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/Power%20Query-ETL-green?style=for-the-badge" />
<img src="https://img.shields.io/badge/Data%20Analytics-Project-orange?style=for-the-badge" />

</p>

---

# 📌 **Project Overview**

The **Tamil Nadu Elections 2021–2026 Power BI Dashboard** is an interactive
**Business Intelligence and Data Analytics project** developed using
**Microsoft Power BI**.

The project focuses on transforming raw election data into **meaningful,
interactive and visually engaging insights**.

The dashboard allows users to explore:

- 🗳️ **Election Results**
- 🏛️ **Constituency-wise Analysis**
- 🏆 **Winner Analysis**
- 🗺️ **Geographical Analysis**
- 📈 **Winning Margin Analysis**
- 📊 **Interactive KPIs and Visualizations**

The project demonstrates an **end-to-end Data Analytics workflow**:

> **Data Cleaning → Data Transformation → Data Modeling → DAX → Visualization → Insights**

---

# 🎯 **Project Objective**

The main objective of this project is to develop an **interactive Power BI
dashboard** that makes Tamil Nadu election data easy to understand and
analyze.

### The dashboard helps answer questions such as:

🔹 Which candidate won each constituency?

🔹 How many votes were received by candidates?

🔹 What were the winning margins?

🔹 Which constituencies had close contests?

🔹 Which constituencies had high-margin victories?

🔹 How are election results distributed geographically?

🔹 How can users interactively explore election results?

---

# 🛠️ **Tools & Technologies**

| 🛠️ Technology | 🎯 Purpose |
|---|---|
| **Power BI Desktop** | Dashboard development & visualization |
| **Power Query** | Data cleaning & transformation |
| **DAX** | Measures & analytical calculations |
| **Data Modeling** | Relationships between tables |
| **Excel / CSV** | Data source & preparation |
| **GitHub** | Project documentation & portfolio |

---

# 📊 **Dashboard Pages**

## 🏠 01. Home Page

The **Home Page** provides an overview of the Tamil Nadu Election
Analysis Dashboard.

It acts as the main navigation page and provides access to different
analytical sections.

### ✨ Features

- 📌 Dashboard overview
- 📊 KPI-based information
- 🔗 Interactive navigation
- 🎨 User-friendly dashboard design
- 📑 Access to different analysis pages

---

## 🗺️ 02. Geographic Analysis

The **Geographic Analysis** page provides a geographical view of
Tamil Nadu election results.

It helps users understand how election outcomes vary across
different constituencies.

### 🔍 Analysis Includes

- 🗳️ Constituency-wise results
- 🗺️ Geographical distribution
- 🏆 Winner information
- 📍 Location-based analysis
- 🔎 Interactive map visualization

---

## 🔄 03. Flip Story

The **Flip Story** page provides an interactive storytelling experience
for exploring election data.

It allows users to navigate between different views and analyze
election information from multiple perspectives.

### ✨ Features

- 🔄 Interactive navigation
- 📊 Dynamic visual analysis
- 📖 Data storytelling
- 🔍 Easy comparison of election information

---

## 📈 04. Winning Margin Analysis

The **Winning Margin Analysis** page focuses on the difference between
winning candidates and their competitors.

### 🔍 Analysis Includes

- 🏁 Close contests
- 📈 High-margin victories
- 🏆 Strong candidate performances
- 📊 Constituencies with significant winning margins

---

# 🧹 Data Cleaning & Transformation

Before developing the dashboard, the election data was prepared and
transformed using **Power Query**.

### 🔧 Data Preparation Steps

- ✔️ Removed unnecessary columns
- ✔️ Handled missing values
- ✔️ Checked duplicate records
- ✔️ Corrected data types
- ✔️ Standardized column names
- ✔️ Cleaned categorical values
- ✔️ Prepared tables for analysis
- ✔️ Transformed raw data into analytical format

> **Power Query** was used for the complete data cleaning and
> transformation process.

---

# 🏗️ Data Modeling

A structured data model was created in Power BI to support efficient
analysis and interactive filtering.

### 📂 Main Analytical Tables

- **FactElection**
- **DimConstituency**
- **Winner**
- **Margin**

### 🧩 Data Modeling Concepts

- 🔹 Fact & Dimension Tables
- 🔹 Table Relationships
- 🔹 Primary & Related Keys
- 🔹 Filter Propagation
- 🔹 Data Model Optimization
- 🔹 Star Schema Concepts

 ---
 
# 🧮 **DAX & Measures**

**DAX (Data Analysis Expressions)** was used to create calculated
measures and KPIs for analyzing election data.

### 📌 **Key DAX Calculations**

#### 🗳️ Total Votes

**Formula:**

`Total Votes = SUM(FactElection[Votes])`

#### 🏛️ Total Constituencies

**Formula:**

`Total Constituencies = DISTINCTCOUNT(DimConstituency[Constituency])`

#### 👤 Total Candidates

**Formula:**

`Total Candidates = DISTINCTCOUNT(FactElection[Candidate])`

### 🎯 **DAX Used For**

- 📊 **KPI Calculations**
- 🗳️ **Vote Analysis**
- 👤 **Candidate Analysis**
- 🏛️ **Constituency Analysis**
- 📈 **Winning Margin Analysis**
- 🔄 **Dynamic Calculations**
- 🎛️ **Interactive Filtering**

---

# 📊 **Dashboard Features**

### 🎯 Interactive Visualizations

The dashboard uses interactive Power BI visuals to make complex election
data easier to understand and explore.

### 📌 KPI Analysis

Important election metrics are presented through KPI cards to provide
a quick overview of election performance.

### 🗺️ Geographic Visualization

The dashboard provides geographical analysis of election results across
different constituencies.

### 🏛️ Constituency Analysis

Users can explore election results at the constituency level and
analyze candidate performance.

### 🏆 Winner Analysis

The dashboard provides insights into winning candidates and their
election performance.

### 📈 Winning Margin Analysis

Users can analyze the difference between winning candidates and their
competitors.

### 🎛️ Interactive Filters

Slicers and filters allow users to dynamically explore specific parts
of the election dataset.

---

# 🔍 **Key Insights**

The dashboard helps users identify meaningful patterns and insights
from the election data, including:

- 🗳️ **Constituency-wise election outcomes**
- 👤 **Candidate vote performance**
- 🏆 **Winning candidate information**
- 📈 **Winning margins**
- 🗺️ **Geographical distribution of election results**
- ⚔️ **Close election contests**
- 🥇 **High-margin victories**
- 📊 **Differences in election performance across constituencies**

---
# 🔄 **Project Workflow**

The project follows an end-to-end data analytics workflow:

1. 📥 **Raw Election Data**
   ↓
2. 🧹 **Data Cleaning**
   ↓
3. 🔄 **Power Query Transformation**
   ↓
4. 🏗️ **Data Modeling**
   ↓
5. 🧮 **DAX Measures**
   ↓
6. 🎨 **Dashboard Design**
   ↓
7. 📊 **Interactive Visualizations**
   ↓
8. 💡 **Business Insights**


---

# 📸 **Dashboard Preview**

## 🏠 **Home Dashboard**

![Home Dashboard](Home.png)

---

## 🗺️ **Geographic Analysis**

![Geographic Analysis](Geography%20story.png)

---

## 🔄 **Flip Story**

![Flip Story](Flip%20story.png)

---

## 📈 **Winning Margin Analysis**

![Winning Margin Analysis](Margin%20analysis.png)

---

# 💡 **Skills Demonstrated**

## 📊 **Power BI Skills**

- **Power BI Desktop**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Table Relationships**
- **KPI Cards**
- **Slicers & Filters**
- **Interactive Visualizations**
- **Dashboard Design**
- **Data Storytelling**

## 📈 **Data Analytics Skills**

- **Data Cleaning**
- **Data Transformation**
- **Exploratory Data Analysis**
- **KPI Development**
- **Comparative Analysis**
- **Pattern Identification**
- **Business Intelligence**

## 🧠 **Analytical Skills**

- **Problem Solving**
- **Data Interpretation**
- **Insight Generation**
- **Data Storytelling**
- **Business Thinking**
- **Dashboard Development**

---

# 🎓 **Learning Outcomes**

This project helped me strengthen my practical understanding of the
complete **Power BI development lifecycle**.

### Through this project, I learned how to:

- ✔️ Import and prepare raw data
- ✔️ Clean and transform data using Power Query
- ✔️ Build relationships between tables
- ✔️ Create a structured data model
- ✔️ Develop DAX measures
- ✔️ Create interactive dashboards
- ✔️ Design meaningful KPIs
- ✔️ Use geographical visualizations
- ✔️ Analyze winning margins
- ✔️ Present insights through data storytelling

---

# 🚀 **Future Improvements**

The dashboard can be further enhanced by adding:

- 📅 **Advanced election-year comparison**
- 🏛️ **Party-wise performance analysis**
- 👤 **Detailed candidate-level analysis**
- 📈 **Advanced DAX calculations**
- 🗺️ **Additional geographical insights**
- 📊 **Trend analysis**
- 🔎 **Drill-through pages**
- 🎛️ **Advanced dashboard navigation**
- 📌 **Additional analytical KPIs**

---

# 📌 **Project File**

### 📊 TamilNadu-Elections-2021-2026-PowerBI.pbix

The main Power BI report contains:

- 📊 Interactive dashboards
- 🧹 Data transformations
- 🏗️ Data model
- 🧮 DAX measures
- 🎨 Data visualizations
- 🎛️ Interactive filters
- 📈 Election analysis

---

# 👩‍💻 **About Me**

## **Payal Rana**

### 🎯 Aspiring Data Analyst | Power BI | SQL | Python | Excel

I am passionate about **Data Analytics and Business Intelligence** and
interested in transforming raw data into meaningful insights.

I enjoy working with data, building interactive dashboards and using
data-driven approaches to solve analytical problems.

### 💻 **Technical Skills**

- 📊 **Power BI**
- 🗄️ **SQL**
- 🐍 **Python**
- 📗 **Excel**
- 🧮 **DAX**
- 🔄 **Power Query**
- 🏗️ **Data Modeling**
- 📈 **Data Visualization**
- 🔍 **Data Analysis**

---

# 📈 **Project Highlights**

This project demonstrates an end-to-end **Business Intelligence workflow**:

📥 **Data Collection**  
↓  
🧹 **Data Cleaning**  
↓  
🔄 **Data Transformation**  
↓  
🏗️ **Data Modeling**  
↓  
🧮 **DAX Measures**  
↓  
📊 **Data Visualization**  
↓  
🎨 **Dashboard Development**  
↓  
💡 **Business Insights**

---

# 📬 **Connect With Me**

### 🔗 LinkedIn

👉 [**Connect with me on LinkedIn**](https://www.linkedin.com/in/payal-rana-914001250/)

### 💻 GitHub

👉 [**View my GitHub Profile**](https://github.com/Payal123-rana)

---

# ⭐ **Thank You**

Thank you for visiting my **Tamil Nadu Elections 2021–2026 Power BI
Dashboard** project.

If you found this project useful or interesting, feel free to ⭐ the
repository and connect with me on LinkedIn.

---

<p align="center">

### 🚀 Turning Data Into Insights With Power BI

**#PowerBI #DataAnalytics #DataAnalyst #DAX #PowerQuery #SQL #Python #Excel #BusinessIntelligence**

</p>





<img width="883" height="496" alt="Screenshot 2026-08-20 113954" src="https://github.com/user-attachments/assets/716c9ab5-11db-4720-858a-97e5e5d40326" />

<img width="877" height="491" alt="Screenshot 2026-08-20 114018" src="https://github.com/user-attachments/assets/c0a871cf-da4c-49f8-9122-5c5f2c9bf5b7" />

<img width="877" height="494" alt="Screenshot 2026-08-20 114115" src="https://github.com/user-attachments/assets/13a15472-71cb-4b02-9030-a51fb52e3eb7" />

<img width="883" height="494" alt="Screenshot 2026-08-20 114136" src="https://github.com/user-attachments/assets/e52b5479-c474-4537-a8e9-f380f38151f7" />









































