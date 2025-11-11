# 📊 Sales & Customer Dashboards

## Overview  
This Tableau project delivers **interactive dashboards** for analyzing **sales performance** and **customer insights**.  
It helps users explore trends, identify key customers, and measure growth across years and regions — all in one visual workspace.

🔗 **Live Dashboard:** [View on Tableau Public](https://public.tableau.com/views/SalesCustomerDashboards_17628010778810/CustomerDashboard)

---

## 🔧 Contents  
- **Sales Dashboard** – Highlights overall sales performance, profit trends, and year-over-year growth.  
- **Customer Dashboard** – Shows customer segmentation, order frequency, and total contribution to sales.  
- **Dynamic Filters** – Filter by **Year**, **Region**, and **Customer Name** for personalized analysis.  
- **Custom Icons** – Visual navigation with clear active/inactive states for user-friendly interaction.

---

---

## 🚀 How to Use  
1. Open the `.twbx` file in **Tableau Desktop (2021.1 or later)**.  
2. Navigate between dashboards using the icons or tabs.  
3. Apply filters for **Year**, **Customer**, or **Region** to view specific insights.  
4. Hover over visuals for detailed metrics and tooltips.

---

## 📈 Key Metrics & Calculated Fields  
- **YoY Growth %** → `(SUM([CY Sales]) - SUM([PY Sales])) / SUM([PY Sales])`  
- **Customer Count (Distinct)** → `COUNTD([Customer Name])`  
- **Sales per Customer** → `SUM([Sales]) / COUNTD([Customer Name])`  
- **Profit Ratio** → `SUM([Profit]) / SUM([Sales])`  
- **Top N Customers** → Dynamic parameter-based ranking using `INDEX()`  

---

## 💡 Key Insights  
- Identify **top-performing customers** and their revenue contribution.  
- Compare **Current vs Previous Year** performance visually.  
- Measure **regional performance** and detect underperforming areas.  
- Understand **customer retention** and **sales growth** trends.  

---

## 🧩 Tools Used  
- **Tableau Desktop** – Visualization & dashboard creation  
- **Tableau Public** – Online publishing and sharing  
- **Excel / CSV Datasets** – Sales and customer records  

---

## 🧠 Author  
**Suresh Reddy**  
📬 Connect on [LinkedIn](https://www.linkedin.com/in/mallidi-sai-suresh-reddy/) | 🌐 [Tableau Public Profile]([https://public.tableau.com/app/profile/sai.suresh.reddy.mallidi7672/vizzes])

