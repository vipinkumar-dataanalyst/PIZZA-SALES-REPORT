# PIZZA-SALES-REPORT

## 📈 Dashboard Pages

### ⭐ 1. Home
- High-level KPIs  
- Revenue trend using Line Chart  
- Category/Size share using Donut Chart  
- Navigation buttons for smooth page switching  

### 🔥 2. Best & Worst Seller Dashboard
- Bar chart for **Top 5 Best Selling Pizzas**  
- Bar chart for **Bottom 5 Worst Selling Pizzas**  
- Filters for category, size, and date  
- Performance comparison  

---

## 🧠 Insights Generated
- Identified top performing pizza categories and items  
- Recognized low-performing pizzas  
- Analyzed order volume and revenue patterns  
- Visualized revenue growth trend  

---

## 🧰 Power BI Features Used
- DAX Measures  
- Page Navigation Buttons  
- Bar Chart, Line Chart, Donut Chart  
- Slicers for filtering  
- Clean UI/UX Design  

---

## 🚀 How to Use
1. Clone or download the repository  
2. Load the dataset  
3. Run SQL scripts to clean & model the data  
4. Import final tables into Power BI  
5. Add DAX measures  
6. Open the `.pbix` file to view and interact with the dashboard  

---

### Screenshots / Damos
Show what the dashboard looks like :

<img width="1301" height="732" alt="HOME" src="https://github.com/user-attachments/assets/f09b23ec-4362-4c65-bb04-4891f001901b" />

<img width="1309" height="730" alt="BEST AND WORST SALLER" src="https://github.com/user-attachments/assets/836a894e-3429-4734-8245-c168f8fbf9c9" />


## 🧩 DAX Measures

```DAX
Total Revenue = SUM(pizza_sales[total_price])

Average Order Value = [TOTAL REVENUE]/[TOTAL ORDER]

Total Pizzas Sold = SUM(pizza_sales[quantity] )

Total Orders = DISTINCTCOUNT(pizza_sales[order_id])

Average Pizzas Per Order = [TOTAL PIZZAS SOLD]/[TOTAL ORDER]

