# 🏨 Hotel Booking Analysis | Power BI

<p align="center">
  <strong>Transforming Hotel Booking Data into Business Insights</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
  <img src="https://img.shields.io/badge/DAX-Measures-512BD4?style=for-the-badge" alt="DAX"/>
  <img src="https://img.shields.io/badge/Data%20Modeling-Analytics-1F6FEB?style=for-the-badge" alt="Data Modeling"/>
  <img src="https://img.shields.io/badge/Project-Hotel%20Analytics-217346?style=for-the-badge" alt="Hotel Analytics"/>
</p>

---

## 📌 Project Overview

The **Hotel Booking Analysis Dashboard** is a business intelligence project developed using Microsoft Power BI to analyze hotel booking data, revenue performance, customer activity, and stay-related metrics.

The project demonstrates how data preparation, dimensional data modeling, DAX calculations, and interactive visualizations can be combined to create a structured analytical report.

The dashboard is designed to help users explore booking performance and understand key metrics through a clear, interactive reporting experience.

## 🎯 Business Objectives

- 📅 Analyze hotel booking activity and booking trends.
- 💰 Evaluate revenue performance.
- 👥 Understand customer-related metrics.
- 🛏️ Examine booking and room-related information.
- 🌙 Analyze the number of nights associated with bookings.
- 📊 Develop key performance indicators (KPIs).
- 🔎 Enable interactive exploration through report filters and visualizations.

## 🛠️ Tools & Technologies

| Technology | Purpose |
|---|---|
| Microsoft Power BI Desktop | Dashboard development and reporting |
| Power Query | Data preparation and transformation |
| DAX | Measures and analytical calculations |
| Data Modeling | Connecting fact and dimension tables |
| Power BI Visuals | Presenting KPIs and analytical results |
| Microsoft Excel / Source Data | Data source, where applicable |

## 🗂️ Data Model

The Power BI model contains a central fact table supported by dimension tables for customer, hotel, room, and calendar information.

### Fact Table

**`FactBooking`**

The central table for booking-related analysis.

It supports the analysis of booking records, revenue, and stay-related metrics using the fields available in the dataset.

### Dimension Tables

**`DimCustomer`**

Supports customer-related analysis using customer attributes.

**`DimHotel`**

Contains hotel-related information for hotel-level analysis.

**`DimRoom`**

Supports room-related analysis using the room attributes available in the model.

**`DimCalendar`**

Supports date-based analysis and time filtering.

### Conceptual Data Model

```text
              DimCustomer
                   |
                   |
DimHotel ---- FactBooking ---- DimRoom
                   |
                   |
              DimCalendar
```

*Note: This is a conceptual representation of the model tables. Confirm the actual relationships, cardinality, and filter directions in Power BI Model view before treating the diagram as the final relationship design.*

## 🔗 Data Modeling Approach

The model separates booking transactions from descriptive information to support structured analysis.

Key modeling concepts demonstrated in the project include:

- Fact and dimension tables
- Table relationships
- Primary and foreign key concepts
- Cardinality and filter direction
- Date-based analysis
- Filter propagation across related tables

The actual relationship settings should be documented from the saved Power BI model.

## 🧹 Data Preparation

Data preparation is an important part of building a reliable Power BI report.

The project's documentation should cover the transformations actually performed, such as:

- Checking column names and data types
- Reviewing missing and inconsistent values
- Preparing columns for analysis
- Verifying key fields used in relationships
- Ensuring numeric fields support the intended calculations

*Only transformations that were actually performed should be listed as completed steps.*

## 🧮 DAX Measures & KPIs

The report includes booking and revenue-related measures.

| Measure | Purpose |
|---|---|
| Total Booking | Measures booking activity |
| Total Revenue | Calculates revenue |
| Total Guest | Represents the customer-related metric defined in the model |
| Total Night | Represents the night-related metric defined in the model |
| Avg Revenue | Calculates a revenue-based average according to its formula |

DAX measures allow report values to respond dynamically to the current filter context.

### DAX Concepts

- Aggregation functions such as `SUM`
- Counting functions such as `COUNTA` and `DISTINCTCOUNT`
- `DIVIDE` for safe division
- Filter context
- Dynamic KPI calculations

*The precise definitions of the measures should be checked against their actual DAX formulas before publishing this documentation.*

## 📊 Dashboard & Report

The report includes an **Executive Overview** page.

This page serves as the main entry point for viewing the report's key metrics and visualizations.

The final documentation should include a screenshot of the actual dashboard and a description of the visuals and filters present in the saved report.

## 🔍 Business Questions

The report is intended to support questions such as:

1. How many bookings are recorded?
2. What is the total revenue?
3. How does booking activity change across the available dates?
4. What customer-related metrics can be analyzed?
5. How many nights are associated with the bookings?
6. How do the KPIs change when report filters are applied?
7. What booking and revenue patterns can be identified from the available visualizations?

The answers should be based on validated results from the actual report rather than assumed findings.

## 📈 Analytical Workflow

```text
Source Data
     ↓
Data Preparation
     ↓
Data Modeling
     ↓
Relationships
     ↓
DAX Measures
     ↓
KPI Development
     ↓
Dashboard Visualization
     ↓
Business Analysis
```

## 💡 Skills Demonstrated

- Power BI report development
- Data preparation and transformation
- Dimensional data modeling
- Fact and dimension tables
- DAX measures
- KPI calculations
- Interactive reporting
- Data visualization
- Analytical thinking

## 🚀 How to Open the Project

### Requirements

- Microsoft Power BI Desktop
- Access to the source data if an external source is required

### Steps

1. Download the `.pbix` file from this repository.
2. Open the file using Power BI Desktop.
3. Allow the report to load.
4. Explore the Executive Overview page.
5. Interact with available slicers and filters.
6. Open Model view to inspect table relationships.
7. Review the DAX measures and their definitions.

If the report uses an external data source, update its file path or connection settings as required before refreshing.

## 📁 Repository Structure

```text
hotel-booking-analysis-powerbi/
│
├── Hotel_Bookings.pbix
├── README.md
└── screenshots/
    └── executive-overview.png
```

The screenshot folder is optional. Add the screenshot after capturing the actual report page.

## 📚 Learning Outcomes

This project provides practical experience in using Power BI to structure booking data, create analytical measures, build a data model, and present information through an interactive report.

It also highlights the importance of validating formulas, relationships, and source data before drawing business conclusions.

## 📌 Dataset Information

The dataset is used for analytical and portfolio demonstration purposes.

Its conclusions should be interpreted according to the source data, its quality, and the definitions used for the report's measures.

## 🔮 Future Improvements

- Add more detailed booking trend analysis.
- Improve the documentation of DAX calculations.
- Include a visual data model diagram.
- Add validated business insights from the report.
- Publish an interactive report link if appropriate.
- Document source data and refresh requirements.

## 👨‍💻 Author

**[Mohammed Tayib]** – Aspiring Data Analyst
Skills: Excel · SQL · Power BI · DAX · Python
🔗 [LinkedIn](https://www.linkedin.com/in/md-tayib-b67566307/) · 💻 [GitHub](https://github.com/MDTayib)

---

<p align="center">
  <strong>Turning Data into Insights | Learning Through Projects</strong>
</p>
