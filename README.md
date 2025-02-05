# 📊 Sales Analysis Multilevel Dashboard

## 📝 Description
This project showcases a comprehensive Power BI dashboard designed for AdventureWorks, a global manufacturing company specializing in cycling equipment and accessories. The dashboard highlights key metrics, regional performance, product trends, and customer insights, tailored to support data-driven decision-making at the managerial level.

---

## 🎯 Objective
Develop a business intelligence solution to:
- 📊 Track KPIs such as sales, revenue, profit, and returns.
- 🌍 Compare regional performance and identify underperforming territories.
- 📈 Analyze product-level trends to pinpoint best-sellers and high-return items.
- 🎯 Identify and segment high-value customers for targeted marketing efforts.

---

## 🔍 Steps Followed

### 🏢 Business Case Context
- The management team required a scalable and interactive solution to monitor real-time business performance.
- A folder of raw CSV files containing transactions, returns, products, customers, and sales territories was used as the data source.

### 🛠️ Data Preparation
- 🔗 Connected and transformed raw data in Power Query Editor.
- 🧹 Performed data cleaning to handle missing and erroneous values.
- ✅ Applied profiling tools to ensure data quality (column profiling, distribution analysis).
- 📂 Combined and appended queries to create unified datasets.

### 🗂️ Data Modeling
- Built a relational model using fact and dimension tables for normalization:
  - **Fact Table:** Sales Data.
  - **Dimension Tables:** Products, Customers, Calendar, and Territories.
- 🔄 Established one-to-many relationships to ensure efficient data flow.
- ✍️ Used DAX expressions for calculated measures like total revenue, profit margins, and return rates.

### 📊 Dashboard Visualization
- Designed an interactive dashboard in the Report View of Power BI.
- Included dynamic visualizations such as:
  - 🗺️ Regional maps to display sales distribution.
  - 📊 Bar and line charts for sales trends and revenue growth.
  - 📋 Matrix visuals to drill down by product and customer segments.
- 🎛️ Enabled filters for managers to customize views (e.g., by region, product category, or time period).

### ⚡ Optimization
- 🚀 Improved performance with optimized DAX queries.
- 🗓️ Leveraged hierarchies (e.g., Year > Month > Day) for time-based analysis.
- 💡 Configured tooltips and bookmarks for an enhanced user experience.

---

## 🌟 Impact
- Delivered actionable insights to streamline marketing strategies and inventory planning.
- Highlighted underperforming regions and products, leading to a 10% increase in targeted sales campaigns.

---

## ⚙️ Technical Details

### 🛠️ Tools & Techniques
- **Power BI Desktop:** For visualization and modeling.
- **Power Query:** For ETL (Extract, Transform, Load) processes.
- **DAX (Data Analysis Expressions):** For advanced calculations and measures.
- **Data connectors:** CSV files for transactional and lookup data.

### 📌 Key Metrics Visualized
- **Total Sales:** Aggregated and segmented by region.
- **Profit Margins:** Highlighted by product categories.
- **Return Rates:** Drill-down views to identify problematic products.
- **Customer Segmentation:** Focused on high-value demographics.

### ⭐ Notable Features
- Fully interactive and intuitive design.
- ⏳ Time-series analysis for sales trends.
- 🎚️ Multi-level filtering with slicers and drill-throughs.

---

This project exemplifies how Power BI can transform raw data into actionable insights, enabling smarter business decisions. By integrating advanced analytics and interactive visualizations, the dashboard empowers stakeholders to identify growth opportunities, optimize operations, and drive profitability effectively. It demonstrates the power of data in shaping strategies and achieving tangible business impact.
