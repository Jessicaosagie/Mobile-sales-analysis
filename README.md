# 📊 Mobile Sales Analysis  

## 📖 Project Overview  
This project analyzes mobile phone sales data sourced from Kaggle.  
The goal is to uncover customer purchasing trends, payment preferences, and product performance across different demographics and locations.  

Dashboards and reports were built using **Power BI, Excel, and SQL** to provide actionable business insights.  

---

## 📂 Dataset Overview  
- **Source:** Kaggle  
- **Format:** CSV  
- **Size:** 1000+ transactions  

### Sample Records (first 3 transactions)
| InvoiceNo | StockCode | Description  | Quantity | InvoiceDate | UnitPrice | CustomerID | Country |
|-----------|-----------|--------------|----------|-------------|-----------|------------|---------|
| 537226    | 22728     | mobile a     | 6        | 12/1/2010   | 3.75      | 15311      | UK      |
| 537227    | 22729     | mobile b     | 8        | 12/1/2010   | 5.00      | 15312      | UK      |
| 537228    | 22730     | mobile c     | 2        | 12/1/2010   | 7.50      | 15313      | UK      |

---

## ⚙️ Tools Used  
- **Power BI** → Dashboard & Visual Analytics  
- **Excel** → Pivot Tables & Aggregations  
- **SQL** → Data Extraction & Queries  
- **GitHub** → Portfolio & Project Documentation  

---

## 🔑 Key Insights  
- **Total Revenue:** 40.22M  
- **Top Gender by Sales:** Female & Other (13.47M each)  
- **Top Payment Method:** Credit Card (11.30M)  
- **Best-Selling Model:** "huge" (283K revenue)  
- **Top Location by Sales:** Lake Amanda (186K)  
- **Gender Split:** Sales are evenly distributed across Male, Female, and Other.  
- **Online Payments:** Strong growth, generating 10.28M in revenue.  

---

## 📊 Visualizations  

### Power BI Dashboard  

<img width="1138" height="639" alt="Mobile_Sales Dashboard" src="https://github.com/user-attachments/assets/15abff03-02cf-487e-b4a1-79a98a794435" />
  

### Excel Pivot Tables  
<img width="1372" height="499" alt="Pivot Table_Mobile Sales" src="https://github.com/user-attachments/assets/0bbc2f49-9a30-4754-8513-ed1cbdcee922" />  

---

## 🗄️ SQL Queries  

### 1. Find the most expensive brand  
```sql

SELECT TOP 1 Brand, MAX(UnitPrice) AS HighestPrice
FROM mobile_sales
GROUP BY Brand
ORDER BY HighestPrice DESC;
```
---

### 🏷️ Author  

- **Name:** Your Name  
- **Email:** jessica.a.osagie@gmail.com   
- **LinkedIn:** [Your LinkedIn](https://linkedin.com/in/jessica-osagie/)  
