# Task-02-Anchal-Damani
#  Data Analytics Project – Exploratory Data Analysis (EDA) P2

##  Project Overview
This project focuses on **Exploratory Data Analysis (EDA)** of an e-commerce dataset containing customer orders, product details, payment methods, coupon usage, and order statuses.  
The goal is to clean, prepare, and analyze the dataset to uncover insights about customer behavior, product performance, and sales trends.

---

##  Dataset Information
The dataset includes the following key fields:

- **OrderID** – Unique identifier for each order  
- **Date** – Order date (numeric format)  
- **CustomerID** – Unique customer identifier  
- **Product** – Product category (Laptop, Phone, Monitor, etc.)  
- **Quantity** – Number of items purchased  
- **UnitPrice** – Price per item  
- **TotalPrice** – Final order value  
- **PaymentMethod** – Cash, Credit Card, Debit Card, Online, Gift Card  
- **OrderStatus** – Shipped, Delivered, Cancelled, Returned, Pending  
- **CouponCode** – Discounts applied (SAVE10, FREESHIP, WINTER15, etc.)  
- **ReferralSource** – Customer acquisition channel (Instagram, Facebook, Google, Email, Referral)  

---

##  Steps Performed
1. **Data Cleaning**
   - Removed inconsistencies in `UnitPrice` and `TotalPrice`
   - Standardized coupon codes and referral sources
   - Handled missing or duplicate values
   - Converted numeric dates into proper date format

2. **Data Preparation**
   - Added calculated fields (e.g., revenue per product, coupon impact)
   - Categorized payment methods and order statuses
   - Created structured tables for analysis

3. **Exploratory Data Analysis (EDA)**
   - Distribution of products sold
   - Payment method preferences
   - Coupon usage and its effect on sales
   - Order status breakdown (Delivered vs Cancelled vs Returned)
   - Referral source contribution to revenue

---

##  Screenshots

- Raw Data Preview  
  <img width="1192" height="963" alt="Screenshot 2026-06-13 005212" src="https://github.com/user-attachments/assets/4099d81c-5c6c-48af-a677-3cf7bc455f45" />


- Cleaned Data Preview  
  <img width="1725" height="957" alt="Screenshot 2026-06-13 005241" src="https://github.com/user-attachments/assets/c0dc71fa-ebfc-48c8-921f-34e54847a16a" />


- Pivot Analysis 
  <img width="1056" height="962" alt="Screenshot 2026-06-13 005539" src="https://github.com/user-attachments/assets/f30992dd-b439-45d4-b464-e906a82b43f8" />


- Order Analytics Dashboard
  <img width="1535" height="955" alt="Screenshot 2026-06-13 005431" src="https://github.com/user-attachments/assets/c83f7f2a-edfb-4f37-9e42-8130d1e8bfab" />


- Insights Summary
  <img width="995" height="957" alt="Screenshot 2026-06-13 005452" src="https://github.com/user-attachments/assets/c62f0e94-2348-4bf3-af36-2a0063b22bad" />

  

---

##  Key Insights
- **Top Products**: Laptops and Tablets generated the highest revenue.  
- **Coupon Effectiveness**: `SAVE10` and `WINTER15` were the most frequently used coupons.  
- **Order Status**: A significant portion of orders were **Cancelled or Returned**, highlighting potential operational issues.  
- **Referral Sources**: Instagram and Facebook drove the majority of sales, while Google and Email had moderate impact.  
- **Payment Trends**: Credit Card and Cash were the most common payment methods.

---

##  Tools & Technologies
- **Microsoft Excel** – Data cleaning, preparation, and dashboard building  

##  How to Use
1. Download the dataset (`Data Analytics Exploratory Data Analysis (EDA) P2.xlsx`).  
2. Open in Microsoft Excel.  
3. Review the **Raw Data** sheet.  
4. Explore the **Cleaned Data** and **Pivot Tables**.  
5. Navigate to the **Dashboard sheet** for interactive visuals.  

---

##  Project Goals
- Showcase **Excel EDA and dashboard building skills**.  
- Provide actionable insights into **sales and customer behavior**.  
- Demonstrate how raw data can be transformed into **one interactive dashboard** for decision‑making.  

   ```bash
   git clone https://github.com/yourusername/Data-Analytics-EDA-P2.git
