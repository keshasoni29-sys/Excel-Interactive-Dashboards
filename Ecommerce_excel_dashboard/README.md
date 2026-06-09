# 📈 Interactive E-Commerce Sales Dashboard

![Dashboard Preview](dashboard_preview.png)

## 📖 Project Overview
This project delivers a **fully interactive business intelligence dashboard** developed entirely in Microsoft Excel. Designed to provide actionable insights for a retail fashion brand, the dashboard translates raw transaction data into a cohesive visual narrative. It empowers stakeholders to monitor business health, track sales performance, and identify customer trends without the need for expensive or specialized BI software.

---

## 🎯 Business Objectives
The primary goal was to transform three months of transactional data into a dynamic reporting tool that answers critical business questions:
* **Overall Performance:** Tracking key KPIs such as Total Orders, Total Revenue, Average Rating, and Delivery Efficiency.
* **Trend Analysis:** Visualizing weekly revenue and quantity demand over a 13-week period.
* **Customer Segmentation:** Analyzing purchase behavior by gender and sales channel (e.g., App, Website, Retail Partners).
* **Regional Insights:** Geospatial mapping of order volume and revenue by county.

---

## 🛠 Technical Implementation
* **Data Processing:** Leveraged **Pivot Tables** for efficient data aggregation and dynamic summarization.
* **Custom Metrics:** Developed custom formulas to calculate:
    * *Days to Deliver* (Ship Date - Order Date)
    * *Weekly Time-Series* (using `WEEKNUM`)
    * *Data Normalization* (using `IF` logic to clean gender and category labels).
* **Advanced Visuals:**
    * **Linked Pictures:** Used for dynamic matrix tables that update instantly.
    * **Heat Maps:** Applied conditional formatting to visualize geographic performance.
    * **Interactive UI:** Configured **Slicers** with cross-report connections to allow seamless filtering across all charts.
* **Dashboard Design:** Created a professional, clean user interface using shape-based layouts and a cohesive corporate color scheme.

---

## 🚀 How to Use
1. **Clone or Download** this repository.
2. Open the file `E-Commerce_Dashboard.xlsx` in **Microsoft Excel**.
3. Use the **Slicers** located on the dashboard tab to filter data by *Order Mode* or *Customer Gender*.
4. **Update Data:** If you add new data to the `Data` sheet, go to the **Data** tab in the Excel ribbon and click **"Refresh All"** to update the entire dashboard.

---

## 📁 Repository Structure
```text
├── /data                # Raw transaction data and processing sheets
├── /dashboard           # Final Excel Dashboard file (.xlsx)
├── dashboard_preview.png # Screenshot for the project showcase
└── README.md            # Project documentation
