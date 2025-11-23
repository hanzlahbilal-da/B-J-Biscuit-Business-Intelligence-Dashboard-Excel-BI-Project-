# B-J-Biscuit-Business-Intelligence-Dashboard-Excel-BI-Project-
This project delivers two fully-interactive Business Intelligence Dashboards for B&amp;J Biscuit, built entirely in Microsoft Excel using Power Query, Power Pivot (Data Model), PivotTables, DAX Measures, and advanced visualization techniques.
The dashboards transform raw data into actionable insights, enabling management to make faster, smarter, and more data-driven decisions.

🧱 Dashboard Components
### 📘 Dashboard 1 – Operational Performance & Customer Overview

This dashboard provides a complete snapshot of business health.

✔ Features:

Revenue Breakdown

By Product Tier (High-priced vs Low-priced)

By Age Bracket & Gender

By Payment Method

Profitability Analysis

Top Brand, Location, Customer, Sales Representative

Company-wide Profit Margin

Customer Intelligence

Top 5 customers by revenue

New Customers count

Sales Performance

Total Units Sold

Gross Revenue

COGS

Net Profit

Geographical Overview

Regional revenue distribution

### 📙 Dashboard 2 – Revenue Trend & Financial Analysis

This dashboard focuses on trends and time-based insights.

✔ Features:

Time-Series Performance

QoQ Revenue Trend

MoM Revenue Change

WoW Analysis (Weekday vs Weekend)

Dynamic Revenue Composition

By Product Family

By Age Group, Gender, Location

ViewMode Toggle

Switch between Absolute Values & Percentage Contribution

Key KPIs

Total Revenue

Total Profit

Total Quantity Sold

Total COGS

Average Order Value (AOV)

Annotations

Section to document promotions, events, seasonality

🗂 Data Model & Structure
🧩 Fact Table: Transactions

Transaction Date

Customer Details

Product Code

Quantity Purchased

Sales Representative

Payment Method

Gender

🧩 Dimension Tables

DimProduct → Brand, Cost, Unit Price, Product Family

DimDate → Full calendar table with Year, Month, Quarter, WeekNumber, Day, Weekend Flag

DimCustomer → Customer demographics + First Purchase Date

All tables are created & cleaned using Power Query and loaded into the Excel Data Model with relationships.

🧮 Key DAX Measures

Includes:

Total Revenue

Total COGS

Total Profit

Profit Margin

MoM Change

QoQ Change

WoW Change

Revenue % (for toggle)

Average Order Value (AOV)

🎛 Interactivity

Slicers: Location, Product Family, Payment Method, Gender, Age Group

Toggle: Absolute vs Percentage View

Dynamic charts + KPI cards

Annotated trend explanations

🎨 Design Highlights

Clean, modern layout

KPI cards with icons

Consistent color palette

High-visibility charts

Structured grid layout for Excel dashboards

Professional Notes/Annotation section

📦 Technologies Used

Microsoft Excel

Power Query

Power Pivot / Data Model

DAX (Measures)

PivotTables & Pivot Charts

Data Visualization

📁 Project Files
├── Dashboard_1.xlsx
├── Dashboard_2.xlsx
├── Data_Model_Diagram.png
├── README.md
└── Documentation.pdf (optional)

🚀 How to Use

Open the Excel file

Enable Data Connections

Refresh All

Use slicers & toggle to explore insights

⭐ Key Outcomes

Clear visibility into business performance

Quick identification of trends & anomalies

Better customer segmentation

Profitable product & location insights

Strong foundation for BI-driven decision-making
