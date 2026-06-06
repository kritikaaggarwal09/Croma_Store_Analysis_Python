# 📊 Croma Sales Analytics Project
This project is based on **Croma Sales Analysis** using Python. The main goal of this project is to analyze sales data and generate meaningful business insights through data cleaning, data processing, and visualization techniques. The project demonstrates how sales data can be transformed into useful insights that help understand customer behavior, product performance, payment preferences, city-wise contribution and overall business trends.

---

# 🎯 Objectives 
- 📈 Analyze sales performance
- 🛍️ Identify top-selling products
- 👥 Understand customer purchasing behavior
- 📅 Analyze Yearly and Monthly Sales
- 🌍 Compare city-wise revenue
- 💰 Analyze payment methods
- 📊 Visualize sales trends
- 🔍 Extract useful business insights
- 🐍 Practice Data Analytics using Python
  
---

## 📂 Dataset Details 
The dataset contains information related to:- 


- 👤 Customers:-

     • Customer ID

     • Customer Name

     • City

     • Signup Date


- 🧾 Order_items:-

     •	Order ID

     •	Product ID

     •	Quantity Purchased

     •	Unit Price


- 🛒 Orders:-
  
     •	Order ID
  
     •	Customer ID
  
     •	Order Date
  
     •	Payment Method


- 📦 Products:-
  
     •	Product ID
  
     •	Product Name

     •	Category
  
     •	Base Price



---

# 🔄 Project Workflow
1. 📥 Import dataset
   
    -Imported 4 Datasets into Python using Pandas.
 
2. 💡 Data Understanding
   
   -Analyze Datatypes, sample rows, null values and statistical summary using:
   
   •	Info ()
   •	Describe ()
   
3. 🧹 Data Cleaning
   
    •	Removed duplicate records
   
    •	Correct format type
   
    •	Corrected inconsistent text values
   
    •	Correct spelling
   
5. 🖥️ Handling Missing Values
   
    •	Base price mapping
   
    •	Missing value
   
    •	Forward fill
   
    •	Backward fill
   
7. 📁 Data Merging
   
   -Merged four datasets into one final dataframe.
   
8. ⚙️ Transform Data
   
   Add columns:
   
    • Sales=Quantity * Unit Price
   
    •	Month
   
    •	Year
   
10. 💡Data Visualization
    
    -Create charts to analyze trends and business performance.

---

# 🛠️ Tools and Technologies Used
- 🐍 Python
- 📑 Pandas
- 🔢 NumPy
- 📊 Matplotlib
- 🎨 Seaborn
- 📓 Jupyter Notebook

---

# 📊 Insights Generated 
💰 Total Sales 

🧾 Total Quantity sold

🏆 Best-selling Products 

🏆 Best-selling Category

📅 Yearly sales trends 

📅 Monthly sales trends 

👥 Customer buying patterns 

📦 Product category performance

🌍 City-wise revenue

---

# 🚀 Key Analysis 
Sales/Quantity:--

      Total Sales/Revenue : ₹165023180
      
      Total Quantity sold : 3685
      
      Highest sales in yr : 2024 
      
      Highest Monthly sales : January
      
      Highest selling Product : Dell Inspiron and Laptop Bag are two major selling product
      
      Highest selling category :  Smart phone
      
      Least selling category : Laptop 
      
      Highest sales in city : Delhi 
      
      Least sales in city : Chennai
      
      Highest purchase by customer_id :  C0001
      
      Mosthly payment recived in : Cash
      
      Least payment method used : Debit card


 Quantity:--
 
      Total Quantity sold : 3685
      
      Highest Quantity sold in yr : 2024 
      
      Top sold Product : Dell Inspiron and Laptop Bag are two major sold product
      
      Top Quantity sold category :  Smart phone
      
      Least Quantity sold category : Laptop 


Statistical Analysis:

      Correlation Heatmap: strong correlation (0.78) between quantity and sales, relation between numerical variables.
      
---

# 📊Graphs and Explanations

## •Total Revenue: ₹165023180
💰 Total Revenue represents the overall income generated from product and category sales during the analysis period. It helps measure business performance, sales growth, and the contribution of products or categories toward overall earnings.

Forecasting:

🔮 Total Revenue is useful for future analysis because it helps businesses understand sales performance, identify growth trends, forecast future revenue, and make data-driven decisions. By analyzing total revenue over time, companies can improve marketing strategies, manage inventory efficiently, predict customer demand, and increase overall profitability.

## • Total Quantity: 3685
📦 Total Quantity represents the total number of products sold during the analysis period. It helps businesses understand product demand, sales volume, customer purchasing patterns, and overall market performance.

Forecasting:

🔮 Total Quantity is useful for future analysis because it helps businesses forecast product demand, manage inventory effectively, identify high-selling products, and improve supply chain planning. By analyzing sales quantity trends, companies can make better decisions related to stock management, marketing strategies, and future sales growth.

## • Yearly Sales
📅 Yearly Sales represents the total sales generated within a year. It helps businesses measure annual performance, track growth trends, compare yearly revenue, and evaluate the overall success of sales strategies and business operations.
<img width="768" height="619" alt="Screenshot 2026-06-06 232752" src="https://github.com/user-attachments/assets/482211b4-b953-4df5-8df6-2dee482faeda" />


## • Yearly Quantity   Sold
<img width="728" height="731" alt="Screenshot 2026-06-06 232809" src="https://github.com/user-attachments/assets/dd71a55c-4d59-48f9-a56e-5785a0e7bc08" />


# • Monthly and Yearly Trend
<img width="1441" height="714" alt="Screenshot 2026-06-06 232833" src="https://github.com/user-attachments/assets/96192cb6-fabe-4309-b840-ce15b432bf85" />


# • Monthly Revenue 
<img width="1120" height="729" alt="Screenshot 2026-06-07 002534" src="https://github.com/user-attachments/assets/76d6cb4b-9817-469d-82d3-c9d337b9151d" />


# • Monthly Quantity Sold
<img width="1553" height="706" alt="Screenshot 2026-06-07 002553" src="https://github.com/user-attachments/assets/28f5762e-8f96-4462-831a-f3b63172b938" />


# •Top_product by revenue
<img width="1547" height="634" alt="Screenshot 2026-06-07 002614" src="https://github.com/user-attachments/assets/5344d02e-cea7-436b-a476-b7fbd15f2be3" />


# • Top product by quantity
<img width="1531" height="724" alt="Screenshot 2026-06-07 002637" src="https://github.com/user-attachments/assets/79763088-f3a4-4af2-a08c-12275eff3209" />


# • Category Sales
<img width="802" height="640" alt="Screenshot 2026-06-07 003155" src="https://github.com/user-attachments/assets/8b28dbcf-d8ec-4108-baaf-249ecd65db84" />


# • Category Quantity Sold
<img width="770" height="648" alt="Screenshot 2026-06-07 003215" src="https://github.com/user-attachments/assets/1e4db47e-e401-4d36-8f20-e52a35e788d9" />


# •City Sales
<img width="1193" height="622" alt="Screenshot 2026-06-07 003230" src="https://github.com/user-attachments/assets/10e7dc4b-9eac-494a-b980-983aebd197b5" />


# • Quantity Sold In City 
<img width="1218" height="736" alt="Screenshot 2026-06-07 003244" src="https://github.com/user-attachments/assets/886890cd-dc22-4920-8e40-7c99cebe5ff4" />


# • Highest purchase by customer
<img width="1079" height="622" alt="Screenshot 2026-06-07 003821" src="https://github.com/user-attachments/assets/c89c4461-732d-4d4b-8073-b2b2f8fa42ec" />


# •Highest Quantity of order by Customers
<img width="1135" height="721" alt="Screenshot 2026-06-07 003840" src="https://github.com/user-attachments/assets/42c1b5af-4c3f-44ba-9248-e17b3f682b3f" />


# • Payment method 
<img width="812" height="644" alt="Screenshot 2026-06-07 004018" src="https://github.com/user-attachments/assets/6f02c711-dda1-419b-b45d-fa6ec401092d" />


# • Payment Method Used
<img width="749" height="649" alt="Screenshot 2026-06-07 004029" src="https://github.com/user-attachments/assets/8bbd5075-5f25-473d-9883-b5cd82c5db62" />


# • Correlation
<img width="1583" height="734" alt="Screenshot 2026-06-07 004848" src="https://github.com/user-attachments/assets/51bf2267-8410-43bf-a96d-80573a647964" />

---

# 💡 Business Recommendation 
Based on the sales analysis:-
The business should focus on promoting high-performing products
Improving inventory management for fast-selling items
Promote Digital Payments
Enhancing marketing strategies in regions with strong sales performance
Offer rewards or discounts to retain high – value and repeat customers
Analyzing customer purchasing behavior can help create targeted offers 
Plan for Seasonal Demand
Improve customer satisfaction
Increase overall revenue growth

---

# Conculsion
- 💻 Dell Inspiron and laptop bags generated the highest revenue among all products, making them the top-performing products in terms of revenue contribution.

- 📱 Smartphones are the most sold product category, indicating high customer demand and strong market preference for mobile devices.

- 🌆 Delhi recorded the highest sales compared to all other cities, showing that it is the company’s strongest market location.
   
- 🏆 From a product perspective, Dell Inspiron is the most important product, while smartphones hold the highest importance among all product categories.   
   
- 👥 Customers C0001 and C0005 are identified as the company’s key customers because of their significant contribution to overall sales and revenue.   

- 📈 The company achieved its highest sales performance during the first four months of the year, indicating strong business activity in the initial phase of the year.  

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub

---
   
