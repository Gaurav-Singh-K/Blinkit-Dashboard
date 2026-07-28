# 🛒 Blinkit Sales & Delivery Performance Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Cleaning-green)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

An interactive **Power BI Dashboard** built to analyze **Blinkit Sales, Customer Behavior, Product Performance, and Delivery Operations**. This project provides a complete business intelligence solution with interactive visualizations and KPIs that help monitor business performance, customer purchasing patterns, product sales, and delivery efficiency.

> 📌 Built using **Power BI Desktop**, **Power Query**, and **DAX**.

---

# 📌 Project Overview

This dashboard provides a **360° view** of Blinkit's business performance across multiple dimensions:

- 📈 Sales Performance
- 🛍️ Product Insights
- 👥 Customer Analysis
- 🚚 Delivery Performance
- 📅 Time-Based Trends

The report contains **5 interactive dashboard pages** with filters, slicers, KPIs, and navigation buttons for easy analysis.

---

# 📊 Dashboard Pages

## 🏠 1. Executive Overview

A high-level business summary containing the most important KPIs.

### KPIs
- Total Orders
- Total Revenue
- Average Order Value
- Average Delivery Time
- Fast Delivery %
- High Order %
- Weekend Orders %
- Cities Covered

### Visuals
- Monthly Revenue Trend
- Monthly Orders Trend
- Order Status Distribution
- Orders by Hour & Day Heatmap
- Navigation Buttons

---

## 👥 2. Customer Behavior Analysis

Understand customer purchasing habits and city-wise performance.

### KPIs
- Total Customers
- Average Order Value

### Visuals
- Orders by Order Period
- Average Order Value by City
- Weekend vs Weekday Orders
- City Filter

---

## 📦 3. Product & Category Insights

Analyze product sales and category performance.

### Visuals
- Sales by Category
- Top 10 Products by Revenue
- Category Distribution
- Product Tables
- Category Filter

---

## 🚚 4. Delivery Performance

Track delivery efficiency across different cities.

### KPIs
- Average Delivery Time
- Fast Delivery %

### Visuals
- Delivery Time by City
- Monthly Delivery Trend
- Day-wise Filter

---

## 📅 5. Monthly & Time Trend Analysis

Analyze order trends over time.

### Visuals
- Orders by Month
- Orders by Day
- Orders by Hour
- Time Pattern Treemap

---

# 🧮 Data Model

The report uses a single fact table:

```
new_update_blinkit_dataset
```

### Dataset Columns

| Column | Description |
|----------|-------------|
| Order ID | Unique order identifier |
| Customer ID | Customer identifier |
| City | Delivery city |
| Category | Product category |
| Product Name | Product purchased |
| Quantity Sold | Quantity ordered |
| Price | Product price |
| Total Amount | Order value |
| Order Status | Delivery status |
| Order DateTime | Date & Time of order |
| Order Hour | Order hour |
| Day | Day of week |
| Order Period | Morning / Afternoon / Evening |
| Weekend Label | Weekend / Weekday |
| Delivery Time (mins) | Delivery duration |

---

# 📐 DAX Measures

The dashboard uses custom DAX measures such as:

- Total Orders
- Total Revenue
- Average Order Value
- Average Delivery Time
- Fast Delivery %
- High Order %
- Weekend Orders %
- Total Customers

---

# 🎨 Dashboard Features

- Interactive Power BI Dashboard
- Dynamic KPI Cards
- Drill-down Analysis
- Page Navigation Buttons
- Custom Heat Map
- Interactive Filters & Slicers
- Responsive Layout
- Blinkit-themed Design

---

# 🛠️ Tools & Technologies

| Tool | Purpose |
|------|----------|
| Power BI Desktop | Dashboard Development |
| Power Query | Data Cleaning & Transformation |
| DAX | Measures & KPIs |
| Excel / CSV | Data Source |

---

# 📷 Dashboard Preview

> Add screenshots of each dashboard page inside the **Screenshots** folder.

Example:

---
<img width="1165" height="648" alt="Screenshot 2026-07-28 143913" src="https://github.com/user-attachments/assets/304ce191-2d85-43d5-a8fd-581ae56bd26d" />
<img width="1152" height="648" alt="Screenshot 2026-07-28 143929" src="https://github.com/user-attachments/assets/d88469be-0ec8-4e84-98aa-fb82a1365f77" />
<img width="1152" height="648" alt="Screenshot 2026-07-28 143929" src="https://github.com/user-attachments/assets/f9f62089-5046-4916-87b3-de1c4775cdf1" />

<img width="1158" height="647" alt="Screenshot 2026-07-28 144006" src="https://github.com/user-attachments/assets/baa3b88a-3ad9-4aa1-a600-781dbea707a3" />

<img width="1160" height="647" alt="Screenshot 2026-07-28 144020" src="https://github.com/user-attachments/assets/4ccf3d30-521c-4aff-9b96-5682d1ffc293" />



---

# 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Gaurav-Singh-K/Blinkit-Dashboard.git
```

### 2. Open Power BI

Open

```
Blinkit_Dashboard.pbix
```

using **Power BI Desktop**.

### 3. Update Data Source (Optional)

If prompted, reconnect the report to your local dataset.

### 4. Explore the Dashboard

Use page navigation and slicers to analyze the data interactively.

---

# 📈 Business Insights

This dashboard helps answer questions like:

- Which cities generate the highest revenue?
- Which products contribute the most sales?
- How fast are deliveries across cities?
- When do customers place the most orders?
- What percentage of orders are delivered quickly?
- Which categories perform best?

---

# 📌 Project Highlights

✔ Interactive Dashboard

✔ Business KPIs

✔ DAX Calculations

✔ Power Query Transformations

✔ Customer Analytics

✔ Delivery Analytics

✔ Product Performance

✔ Time Series Analysis

---

# 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository
2. Create a new branch

```
git checkout -b feature-name
```

3. Commit your changes

```
git commit -m "Added new feature"
```

4. Push your branch

```
git push origin feature-name
```

5. Open a Pull Request

---

# 📄 License

This project is licensed under the **MIT License**.


---

# ⭐ Support

If you found this project useful:

⭐ Star the repository

🍴 Fork the repository

💼 Connect on LinkedIn

Happy Learning! 🚀
