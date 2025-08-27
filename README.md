# Brazilian-ecommerce-sales-dashboard-POWER-BI

https://drive.google.com/file/d/1UTooq188oJWUP-4I-Omxi64iJM0G6FiY/view?usp=sharing

This project is a **Power BI Dashboard** built using the [Olist Brazilian E-Commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).  
It provides interactive insights into **orders, payments, sales, and customer distribution** across Brazil.

---

## 📊 Dashboard Features

- **Filters (Slicers)**
  - Year
  - City

- **Charts**
  - 2 Stacked Column Charts  
    - Sales by Year & Payment Type  
    - Price by Year & Order Status  
  - 2 Donut Charts  
    - Sales Share by Payment Type  
    - Orders Share by Status  
  - 2 Stacked Bar Charts  
    - Top 10 Cities by Order Count  
    - Top 10 Cities by Sales & Payment Type  

- **KPIs (Cards)**
  - Total Orders  
  - Total Customers  
  - Total Sales  
  - Average Order Value  

---

## 📂 Dataset

The dataset contains multiple CSV files including:

- `olist_orders_dataset.csv` → Order information (dates, status)  
- `olist_order_payments_dataset.csv` → Payment details (type, value)  
- `olist_order_items_dataset.csv` → Product pricing, freight, and sellers  
- `olist_customers_dataset.csv` → Customer location info (city, state)  
- `olist_geolocation_dataset.csv` → Geographic coordinates  
- `olist_products_dataset.csv` → Product categories  
- `olist_sellers_dataset.csv` → Seller details  
- `olist_order_reviews_dataset.csv` → Customer reviews  
- `product_category_name_translation.csv` → Category translations  

---

## 🔗 Relationships Used

- `orders[order_id]` → `order_items[order_id]`  
- `orders[order_id]` → `order_payments[order_id]`  
- `orders[customer_id]` → `customers[customer_id]`  

---

## 🚀 How to Use

1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).  
2. Open **Power BI Desktop**.  
3. Load the CSV files and set up relationships.  
4. Use the provided visuals structure to build the dashboard.  

---

## 📌 Insights

- Identify which **payment methods** dominate Brazilian e-commerce.  
- Track **yearly sales trends** and delivery performance.  
- Explore the **top cities** driving orders and revenue.  
- Measure overall KPIs like **Total Orders, Total Sales, AOV, and Customers**.  

---

## 🛠️ Tools Used

- [Power BI Desktop](https://powerbi.microsoft.com/)  
- Python (for preprocessing, optional)  
- Kaggle Olist Dataset  

---

## 📷 Dashboard Preview

>  

---

## 👤 Author

- **Your Name**  
- GitHub: [your-username](https://github.com/srinivasprabhas)  
