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

# 📊 Olist KPI Tree (Based on Full Business Questions)

A unified KPI Tree mapping each business question → KPI category → diagnostic metrics.  
Use this to structure SQL scripts, EDA sections, dashboard pages, and your final business insights.

---

# 🎯 TOP-LEVEL GOAL  
## **Increase Total Revenue & Customer Satisfaction**  
Supported by: Conversion, Delivery Efficiency, Payment Behavior, Customer Retention, Product Performance.

---

# 🌿 FULL KPI TREE

---

# 1️⃣ Conversion Funnel KPIs  
Track the customer journey from order → payment → delivery.

### **Primary KPIs**
- **Overall Conversion Rate**
- **Stage-wise Conversion**  
  - Order → Payment  
  - Payment → Shipment  
  - Shipment → Delivery

### **Diagnostic Metrics**
- Funnel drop-off rate (payment pending, failed, cancellations)
- Avg time spent at each funnel stage  
  - Order to Payment  
  - Payment to Shipment  
  - Shipment to Delivery
- Conversion rate by product category
- Conversion rate by region
- Cart abandonment indicators (inferred)

---

# 2️⃣ Logistics & Delivery KPIs  
Measure delivery performance, regional issues, and supply chain efficiency.

### **Primary KPIs**
- **On-Time Delivery %**
- **Average Actual vs Estimated Delivery Time**
- **Delivery Delay Rate**
- **Order Delivery SLA Compliance**

### **Diagnostic Metrics**
- Delay rate by:
  - State / City
  - Seller
  - Product category
  - Carrier (if inferred)
- Delivery delay impact on:
  - Review Scores  
  - Cancellations  
  - Refunds
- Hub/warehouse processing time (based on timestamps)

---

# 3️⃣ Payment Behavior & Revenue KPIs  
Focus on payment patterns, profitability and revenue impact.

### **Primary KPIs**
- **Popular Payment Methods Share**
- **Installment Usage %**
- **Average Installment Count**
- **Total Revenue**
- **Net Revenue (after cancellations/returns)**

### **Diagnostic Metrics**
- Installments vs AOV correlation  
- Payment method preferences by state  
- Installment behavior by order value  
- Category-wise revenue  
- Revenue loss due to:
  - Canceled orders  
  - Returned/refunded orders  
- High-value vs low-value customer segments

---

# 4️⃣ Customer Experience & Review KPIs  
Understand quality perception and customer sentiment.

### **Primary KPIs**
- **Average Review Score**
- **5-Star Rating %**
- **1–2 Star Rate**
- **Delivery Time → Review Score Correlation**

### **Diagnostic Metrics**
- Low-score root causes:
  - Delivery delays  
  - Product quality issues (category-level)  
  - Seller behavior  
- Review distribution across:
  - Product categories  
  - Sellers  
  - Regions  
- Seller satisfaction leaderboard

---

# 5️⃣ Customer Segmentation & Retention KPIs  
Track user lifecycle, loyalty, and repeat behavior.

### **Primary KPIs**
- **Repeat Purchase Rate**
- **Customer Retention Rate**
- **Average Time Between Purchases**
- **Customer Lifetime Orders**

### **Diagnostic Metrics**
- Segments by:
  - Geography  
  - Category preference  
  - Payment behavior  
  - Order value tiers  
- Categories driving the most repeat orders  
- High-value vs low-value customer cohorts  
- New vs returning customer ratio

---

# 6️⃣ Product Category & Sales KPIs  
Analyze category-level performance and profitability.

### **Primary KPIs**
- **Order Volume by Category**
- **Revenue by Category**
- **Category Conversion Rate**
- **Category Cancellation Rate**

### **Diagnostic Metrics**
- Seasonal order trends (month/quarter)
- High refund/return categories
- Top sellers and underperforming sellers for each category
- Stock/out-of-stock inference (via lead times)

---

# 7️⃣ Loss, Risk & Operational Inefficiency KPIs  
Identify hidden financial impact and operational failures.

### **Primary KPIs**
- **Loss Due to Late Deliveries (estimated)**
- **Loss Due to Cancellations**
- **Loss Due to Returns/Refunds**
- **Operational Risk Score (composite)**

### **Diagnostic Metrics**
- Sellers with unusually high cancellation rates  
- Regions with consistent delivery bottlenecks  
- Time-to-ship delays  
- Payment failure & pending statuses  
- SLA breach patterns over time

---

# 8️⃣ Value-Added Predictive/Advanced KPIs  
For machine-learning or advanced analytics layers.

### **Primary KPIs**
- **Optimal Delivery Time Threshold** (maximizes 5-star reviews)
- **5-Star Rating Predictive Variables**
- **Installments → Conversion Impact**
- **Segments Most Sensitive to Delivery Delays**

### **Diagnostic Metrics**
- Feature importance for review predictions  
- Delivery sensitivity scores by customer cohort  
- Installment elasticity (conversion uplift from more options)  
- Churn/retention prediction signals

---

# 🧭 How to Use This Tree
- Map each KPI to SQL queries in your EDA notebook.
- Build dashboard tabs for:
  - Funnel  
  - Delivery  
  - Payments  
  - Revenue  
  - Reviews  
  - Categories  
  - Customers  
- Use the tree to structure the **Insights & Recommendations** section 

---
