Sales Data Analysis Project

This project was completed as part of a Data Science Internship. It focuses on analyzing an online retail dataset to extract meaningful insights related to sales performance, customer behavior, and product trends.

---

Project Objective

The main goals of this project are:
- Identify top-performing products based on revenue  
- Analyze sales trends over time  
- Evaluate country-wise sales performance  
- Generate actionable business insights  

---

Dataset Information

The dataset contains transactional data of an online retail store, including:
- Invoice Number  
- Product Description  
- Quantity  
- Invoice Date  
- Unit Price  
- Customer ID  
- Country  

Dataset Source:  
https://www.kaggle.com/datasets/luisrenterialezano/retail-sales-dataset

---

Data Preprocessing

The following steps were performed:
- Removed missing values from key columns  
- Filtered out negative quantities (returns/cancellations)  
- Converted InvoiceDate to datetime format  
- Created a new column: Revenue = Quantity × Unit Price  

---

Key Performance Indicators (KPIs)

- Total Revenue: 8,911,407.90  
- Top Product: WHITE HANGING HEART T-LIGHT HOLDER  
- Top Country: United Kingdom  

---

Data Visualization

Top 10 Products by Revenue  
![Top Products](top_products.png)

---

Monthly Sales Trend  
![Monthly Sales](monthly_sales.png)

---

Revenue by Country  
![Country Sales](countries.png)

---

Key Insights

- United Kingdom contributes the highest share of total revenue  
- A small number of products generate a large portion of overall sales  
- Sales trends vary across months, indicating seasonal patterns  
- High-performing products should be prioritized for inventory planning  
- Low-performing regions can be improved with better marketing strategies  

---

Project Structure

Sales_Analysis.ipynb  
Report.pdf  
top_products.png  
monthly_sales.png  
countries.png  
README.md  

---

Tools and Technologies

Python  
Pandas  
NumPy  
Matplotlib  
Seaborn  
Jupyter Notebook  

---

Conclusion

This project demonstrates how data analysis can uncover useful insights from raw data and support better business decision-making.
