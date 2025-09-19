# 📊 Mobile Sales Analysis  

## 📑 Table of Contents
- [Project Overview](#-project-overview)
- [Dataset Overview](#-dataset-overview)
- [Tools Used](#-tools-used)
- [Key Insights](#-key-insights)
- [Visualization](#-visualizations)
- [SQL Queries](#-sql-queries)
- [Author](#--author)

## 📖 Project Overview  
This project analyzes mobile phone sales data sourced from Kaggle.  
The goal is to uncover customer purchasing trends, payment preferences, and product performance across different demographics and locations.  

Dashboards and reports were built using **Power BI, Excel, and SQL** to provide actionable business insights.  

---

## 📂 Dataset Overview  
- **Source:** [Kaggle - Mobile Sales Dataset](https://www.kaggle.com/datasets/waqi786/mobile-sales-dataset)   
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
- **Top Mobile Model:** *Huge* model (282.86K revenue).  
- **Gender Split:** Sales are evenly distributed across Male, Female, and Other.  
- **Online Payments:** Strong growth, generating 10.28M in revenue.  

---

## 📊 Visualizations  

### Power BI Dashboard  

<img width="1138" height="639" alt="Mobile_Sales Dashboard" src="https://github.com/user-attachments/assets/15abff03-02cf-487e-b4a1-79a98a794435" />
  

### Excel Pivot Tables  
![Pivot Table_Mobile Sales](https://github.com/user-attachments/assets/ca1d8dde-3463-4eb8-9196-593a87d0e8b5)


---

## 🗄️ SQL Queries  
The following SQL queries were used to extract key insights from the dataset
   
```sql
---Find the most expensive brand----
SELECT TOP 1 Brand, MAX(UnitPrice) AS HighestPrice
FROM mobile_sales
GROUP BY Brand
ORDER BY HighestPrice DESC;


---Top 5 Locations by Total Revenue---
SELECT TOP 5 Location, SUM(TotalRevenue) AS Revenue
FROM mobile_sales
GROUP BY Location
ORDER BY Revenue DESC;

```
---

## 🏷️ Author  

- **Name:** Jessica Osagie  
- **Email:** jessica.a.osagie@gmail.com   
- **LinkedIn:** [LinkedIn](https://linkedin.com/in/jessica-osagie/)  
