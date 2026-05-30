Customer Behavior Analysis — Power BI Dashboard

An interactive Power BI dashboard analyzing customer behavior, 
purchase patterns, and revenue trends across categories and demographics.

---

##  Dashboard Overview

**File:** `Customer_python_project_power_bi_project_file.pbix`  
**Tool:** Microsoft Power BI Desktop  
**Dataset:** Customer Behavior (`customer_behavior customer` table)

---

##  Key KPI Cards

| Metric | Description |
|---|---|
| **Number of Customers** | Total customer count |
| **Average Purchase Amount** | Mean spend per customer (₹) |
| **Average Review Rating** | Mean customer satisfaction score |

---

##  Visuals & Charts

| Visual | Type | Description |
|---|---|---|
| % of Customer Subscription Status | Donut Chart | Breakdown of subscribed vs non-subscribed customers |
| Revenue by Category | Clustered Column Chart | Total purchase amount per product category |
| Sales by Category | Clustered Column Chart | Customer count per product category |
| Revenue by Age Group | Clustered Bar Chart | Revenue distribution across age groups |
| Sales by Age Group | Clustered Bar Chart | Sales volume across age groups |

---

##  Filters / Slicers

- **Gender** — Filter dashboard by customer gender
- **Shipping Type** — Filter by shipping method (e.g., Store Pickup)
- **Category** — Filter by product category
- **Subscription Status** — Filter by subscription type

---

##  Data Model

**Table:** `customer_behavior customer`

**Key Columns used:**
- `customer_id` — Unique customer identifier
- `gender` — Customer gender
- `age_group` — Age demographic group
- `category` — Product category
- `purchase_amount` — Transaction value (₹)
- `subscription_status` — Whether customer is subscribed
- `shipping_type` — Delivery/pickup method
- `review_rating` — Customer review score

Tools & Technologies

- **Microsoft Power BI Desktop**
- **Python** (for data preprocessing)
- **DAX** (for calculated measures)

---

 Author

**Sayantan Saha** 
