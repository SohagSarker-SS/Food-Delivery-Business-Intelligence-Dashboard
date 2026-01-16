# Food Delivery Business Intelligence Dashboard (SQL + Power BI)

## 📌 Project Overview
This project presents an end-to-end Business Intelligence solution for a food delivery platform.  
Using **SQL (PostgreSQL)** for data preparation and **Power BI** for visualization, the dashboard provides a comprehensive view of **business performance, operational efficiency, and customer behavior**.

The goal of the project is to demonstrate practical BI skills: data modeling, KPI design, analytical judgment, and business-oriented storytelling.

---

## ❓ Business Questions Addressed
The dashboard answers key business and operational questions, including:

- How is overall revenue and order volume performing over time?
- Which restaurants drive the most revenue, and which pose operational risk?
- How efficient are delivery riders, and where do delays occur?
- Is customer value concentrated among a small group of users?
- Are customers primarily one-time buyers or repeat users?

---

## 🗂️ Dataset Description
The analysis is based on a structured relational dataset representing a food delivery business, including:

- **Customers** – customer profiles and registration details  
- **Orders** – order-level information (date, time, value, status)  
- **Restaurants** – restaurant details and city information  
- **Deliveries** – delivery status, delivery time, and rider assignment  
- **Riders** – delivery rider information  

The data was cleaned, validated, and transformed in **PostgreSQL**, with a consolidated fact view created for Power BI consumption.

---

## 📊 Dashboard Structure

### Page 1: Executive Performance Overview
Provides a high-level business summary for decision-makers:
- Key KPIs: Total Revenue, Total Orders, Delivered Orders, Cancellation Rate, Avg Delivery Time
- Monthly revenue trend (completed months only)
- Top 10 restaurants by revenue
- Cancellation rate by city
- Orders vs revenue comparison by city
- Interactive slicers (City, Year)
<img width="1513" height="847" alt="image" src="https://github.com/user-attachments/assets/e04e66f4-9ac3-4c7d-9ca3-dea75f98a40f" />


**Purpose:** Understand overall business health and revenue drivers.

---

### Page 2: Rider Performance & Delivery Efficiency
Focuses on operational execution and delivery quality:
- Avg delivery time, delivered orders, and active riders
- Top slowest riders by average delivery time
- Top riders by order volume
- Delivery time distribution (≤20, 21–30, 31–45, >45 minutes)
- City and year slicers for operational drill-down
<img width="1506" height="840" alt="image" src="https://github.com/user-attachments/assets/35016598-c0f3-428d-90b6-7f9c2174f7cc" />


**Purpose:** Identify bottlenecks, rider inefficiencies, and service quality issues.

---

### Page 3: Customer & Restaurant Insights
Explores value concentration and partner risk:
- Total customers, average orders per customer, average revenue per customer
- Top 10 customers by lifetime revenue
- Restaurants with the highest cancellation rates
- Customer order frequency distribution (One-time, Repeat, Loyal)
<img width="1497" height="837" alt="image" src="https://github.com/user-attachments/assets/ac201beb-6719-4f6a-ab11-59d9ff3ef420" />

**Purpose:** Understand customer behavior, revenue concentration, and restaurant risk.

---

## 🔍 Key Insights
- Revenue is driven by a limited number of high-performing restaurants and customers.
- Cancellation rates vary significantly across cities and restaurants, indicating operational risk.
- Average delivery time is driven by a large share of deliveries in the 31–45+ minute range.
- Some riders handle high order volumes while also exhibiting slower delivery times.
- Customer segmentation based on order frequency provided more meaningful insight than value-based segmentation due to skewed sample data.

---

## 🛠️ Tools & Technologies
- **SQL (PostgreSQL)** – data cleaning, validation, and feature engineering  
- **Power BI** – data modeling, DAX measures, and interactive dashboards  
- **DAX** – KPI calculations and analytical metrics  

---

## ▶️ How to Use the Dashboard
1. Download the `.pbix` file from the repository.
2. Open it in **Power BI Desktop**.
3. Use slicers (City, Year) to interact with the visuals.
4. Navigate across pages for executive, operational, and customer-level insights.

---
## Author
**Sohag Sarker**<br>
MSc in Economics & Business Administration – Management Accounting<br>
University of Southern Denmark

