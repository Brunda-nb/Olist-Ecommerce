BUSINESS GOAL
│
├── 1. Revenue Growth
│     │
│     ├── GMV (Gross Merchandise Value)
│     │     ├── Total Orders
│     │     ├── Average Order Value (AOV)
│     │     └── Revenue by Category/Seller
│     │
│     ├── Payment Metrics
│     │     ├── Payment Method Share
│     │     ├── Avg Installments
│     │     └── Installment Revenue Contribution
│     │
│     └── Revenue Leakage
│           ├── Cancellation Rate
│           └── Return/Refund Rate
│
├── 2. Operational Efficiency
│     │
│     ├── Logistics KPIs
│     │     ├── On-time Delivery Rate
│     │     ├── Avg Delivery Time
│     │     ├── Avg Delay (Actual–Estimated)
│     │     ├── Shipping Distance
│     │     └── Late Delivery % by Region
│     │
│     └── Seller Performance
│           ├── On-time Shipment Rate
│           ├── Seller Review Score
│           └── Complaint Rate
│
└── 3. Customer Experience & Retention
      │
      ├── Review Performance
      │     ├── Avg Review Score
      │     ├── Review Distribution (1–5)
      │     └── % Low-rated Orders (<=2)
      │
      ├── Funnel Experience
      │     ├── Placed → Approved Rate
      │     ├── Approved → Shipped Rate
      │     └── Delivered → Reviewed Rate
      │
      └── Customer Behavior
            ├── Unique Customers / Month
            ├── Repeat Customer Rate
            └── Lifetime Value (LTV) 

# 📊 Olist E-Commerce KPI Tree

A KPI Tree breaking down the overall business goal → core KPIs → diagnostic metrics.  
This helps structure the entire analytics project and guide the EDA, funnel analysis, and dashboards.

---

## 🎯 **Top-Level Business Goal**
### **Maximize Gross Merchandise Value (GMV)**  
GMV = Total Orders × Average Order Value (AOV)

---

## 🌿 **KPI Tree Structure**

---

## 1️⃣ **Total Orders**
Total number of completed purchases.

### 🔹 1.1 Customer Growth
- **New Customers**
- **Returning Customers**
- **Customer Acquisition Rate**
- **Churn Rate**

### 🔹 1.2 Order Frequency
- **Orders per Customer**
- **Repeat Purchase Rate**
- **Customer Lifetime Orders**

### 🔹 1.3 Conversion Funnel Metrics
**Traffic → Add to Cart → Checkout → Payment → Order Placed**

- **Product Page Views**
- **Add-to-Cart Rate**
- **Checkout Initiation Rate**
- **Payment Success Rate**
- **Cart Abandonment Rate**
- **Checkout Abandonment Rate**

---

## 2️⃣ **Average Order Value (AOV)**
AOV = Revenue / Total Orders

### 🔸 2.1 Basket Impact
- **Average Basket Size (items/order)**
- **Average Price Per Item**

### 🔸 2.2 Category Mix
- **High-ticket vs Low-ticket category share**
- **Category contribution to revenue**

### 🔸 2.3 Discount & Pricing
- **Discount Rate**
- **Effective Selling Price**
- **Revenue Loss due to Discounts**

---

## 3️⃣ **Operational KPIs (Supporting GMV)**

---

## 3.1 🚚 Delivery & Logistics
Directly influences cancellations & customer satisfaction.

- **Delivery Time**
- **Delay Rate**
- **On-Time Delivery %**
- **Carrier Performance Score**
- **Hub Processing Time**

---

## 3.2 🔁 Order Cancellations & Returns
Cancellations reduce GMV, returns reduce net revenue.

- **Cancellation Rate**
- **Return Rate**
- **Refund Time**
- **Cancellation Reasons (Customer / Seller / Payment)**

---

## 3.3 ⭐ Customer Experience
Higher satisfaction → higher repeat purchases.

- **Customer Review Score**
- **NPS (if available)**
- **Complaint Rate**
- **Support Ticket Time-to-Resolution**

---

## 4️⃣ **Financial KPIs**

---

## 4.1 💰 Revenue Metrics
- **Gross Revenue**
- **Net Revenue (after cancellations/returns)**
- **Revenue by Category**
- **Revenue by State / City**

---

## 4.2 💸 Cost Metrics
Not fully available in Olist dataset, but implied:

- **Logistics Cost (inferred)**
- **Marketing Cost (if doing advanced projects)**

---

