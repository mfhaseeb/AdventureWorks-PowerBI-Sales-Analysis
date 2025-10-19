# AdventureWorks-PowerBI-Sales-Analysis
This project is an advanced interactive dashboard built in **Microsoft Power BI** using the canonical **AdventureWorks** dataset. It serves as a comprehensive business intelligence solution for analyzing sales, profit, and financial performance across various dimensions.


## 🚀 Key Business Insights

The dashboard provides management with critical views for strategic decision-making:

* **Sales Performance:** Tracking sales volume, profit margins, and trend analysis over time.
* **Customer Analysis:** Segmenting customers by key metrics to identify top-tier clients.
* **Geographic Breakdown:** Visualizing sales performance across different regions and countries.
* **Product Performance:** Identifying top and bottom-selling product categories and subcategories.

---

## 🛠️ Technical Skills Demonstrated (DAX & Modeling)

The complexity and value of this project lie in the advanced techniques used in Power BI's underlying data model and DAX language:

### 1. **Advanced Data Modeling**
* **Star Schema Implementation:** The data is structured using a **Star Schema** (Fact tables for Sales/Finance and Dimension tables for Product, Customer, Geography, Date) to ensure efficient query performance and scalability.
* **Relationships:** Correctly defining one-to-many relationships with appropriate filter directions.

### 2. **DAX (Data Analysis Expressions) Measures**
The report is driven by custom DAX formulas, showcasing expertise in complex calculations:
* **Time Intelligence:** Implementing measures like **Year-Over-Year (YoY) Growth**, **Month-to-Date (MTD)** sales, and **Rolling Averages** (using `DATEADD` and `DATESMTD`).
* **Context Manipulation:** Using functions like `CALCULATE` and `ALL` to override filter context for accurate profit margin and gross margin calculations.
* **KPI Creation:** Defining clear Key Performance Indicator (KPI) measures for profitability and efficiency.

### 3. **Visualization & Report Design**
* **Report Interactivity:** Utilizing slicers, filters, and cross-filtering effects to allow users to drill down into specific data segments.
* **Design Principles:** Applying data visualization best practices for layout, color, and chart selection to ensure clarity and user-friendliness.

