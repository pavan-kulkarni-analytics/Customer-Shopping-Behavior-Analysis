# Customer-Shopping-Behavior-Analysis
## 📷 Dashboard Preview

![Power BI Dashboard](images/dashboard.png)

---

## 📊 Key Business Questions Solved

### 🔹 Revenue Analysis
- Total revenue by gender
- Revenue contribution by age group

### 🔹 Customer Insights
- New vs Returning vs Loyal customers
- Top spending (VIP) customers
- Repeat buyers vs subscription behavior

### 🔹 Product Analysis
- Top 5 highest-rated products
- Most purchased products by category

### 🔹 Discount Analysis
- Discount usage percentage
- Which gender uses discounts more
- Products with highest discount usage

### 🔹 Shipping Analysis
- Comparison between Standard vs Express shipping spending

---

## 🧠 Key Insights
- Loyal customers contribute significantly higher revenue
- Discount strategies increase purchase conversion
- Certain categories dominate total revenue
- Repeat buyers are more likely to subscribe

---

## 📈 Dashboard Features (Power BI)
- Interactive filters (Gender, Age Group, Category)
- Revenue KPI cards
- Product performance charts
- Customer segmentation visuals

---

## 🗄️ SQL Highlights
- Aggregations (SUM, AVG, COUNT)
- Window Functions (ROW_NUMBER)
- Subqueries
- CASE statements for segmentation

Example:
```sql
SELECT gender, SUM(purchase_amount) AS revenue
FROM customer
GROUP BY gender;

