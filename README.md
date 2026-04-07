# 📊 E-commerce Funnel Analysis (Python + SQL)

## 🔍 Overview
This project analyzes user behavior using e-commerce clickstream data to build a session-based conversion funnel.

The objective is to identify drop-offs across key stages of the user journey and provide actionable insights to improve conversion rates and revenue.

---

## 📁 Dataset
- Source: Kaggle  
- Link: https://www.kaggle.com/datasets/wafaaelhusseini/e-commerce-transactions-clickstream/data  

This is a synthetic multi-table dataset simulating an e-commerce platform, including user sessions, clickstream events, and transactions. :contentReference[oaicite:0]{index=0}

Tables used in this project:
- `events` → user actions (page_view, add_to_cart, checkout, purchase)
- `sessions` → traffic source, device, country
- `orders` → revenue-related data
---

## 🛠️ Tools & Technologies
- Python (Pandas, Matplotlib, Seaborn)
- SQL (SQLite)
- Jupyter Notebook

---

## 📊 Analysis Performed

### 1. Conversion Funnel
Built a 4-stage funnel:
- page_view → add_to_cart → checkout → purchase

### 2. Conversion & Drop-off Analysis
- Calculated conversion rates between stages
- Identified drop-off points in the funnel

### 3. Traffic Source Analysis
- Compared conversion rates across channels (organic, paid, referral, etc.)

### 4. Device Analysis
- Compared user behavior across mobile, desktop, and tablet

### 5. Revenue Analysis
- Total revenue
- Average Order Value (AOV)
- Revenue by payment method

### 6. SQL Validation
- Reproduced key metrics using SQL queries

---

## 📈 Key Findings

- Total sessions (page_view): 120,000  
- Conversion to purchase: ~28%  
- Largest drop-off: cart → checkout (~45%)  
- Checkout → purchase conversion is strong (~75%)  

- Total revenue: ~$4.49M  
- Average Order Value (AOV): ~$133  

- Conversion rates are relatively consistent across traffic sources (~27–28%)  
- Mobile and desktop users show similar behavior  

---

## 🧠 Business Insights

The most critical bottleneck occurs between add_to_cart and checkout.

Users demonstrate strong purchase intent by adding products to the cart but fail to proceed to checkout. This suggests friction in the checkout initiation process.

Possible causes include:
- Complex checkout flow  
- Hidden costs (shipping, taxes)  
- Lack of trust or payment confidence  

---

## 🚀 Recommendations

- Simplify and optimize the checkout process  
- Improve pricing transparency  
- Add trust signals (reviews, secure payments)  
- Optimize cart UX  
- Run A/B tests on checkout experience  

---

## 📌 Project Structure
├── notebook.ipynb
├── events.csv
├── sessions.csv
├── orders.csv
├── README.md

---

## 💡 Conclusion

This project demonstrates how data analysis can uncover actionable insights to improve conversion and revenue without increasing traffic.

---

## 👩‍💻 Author
Fereshteh Safarkhani  
Data Analyst | Product Analytics
