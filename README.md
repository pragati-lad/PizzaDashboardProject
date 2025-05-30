# Objectives

Analyze pizza sales performance across categories, sizes, and time periods to optimize: Inventory planning
                                                                                        Marketing strategies  
                                                                                        Sales promotions
                                                                                        
# Data Overview

The dataset used contains sales transactions from a pizza restaurant

## Features of dataset:

order_id, pizza_id,
order_date,
order_time

pizza_name, 
pizza_size (S, M, L, XL, XXL), 
pizza_category (Classic, Chicken, Supreme, Veggie)

quantity,
unit_price, 
total_price


# Calculated fields:

Total Sales: [Quantity] * [Unit Price]

Avg. Order Value: AVG([Total Price])

% of Total Revenue: SUM([Total Price]) / TOTAL(SUM([Total Price]))

Rank by Category: RANK_UNIQUE(SUM([Quantity]))


# Key Performance Indicators

| **Metric**               | **Value**            | 
|--------------------------|----------------------|
| **💰 Total Sales**       | `$817,860.05`        | 
| **🛒 Total Orders**      | `21,350`             |  
| **📦 Avg. Order Value**  | `$16.82`             |  
| **🏆 Top-Selling Pizza** | `The Classic Deluxe` |  



# Visuals and Charts:

### **1. Packed Bubble Chart**  
- Shows quantity by pizza name/size.  
- Bubble size = order volume; color = pizza size.  

### **2. Sales Distribution**  
- **Pie Chart**: % revenue by category.  
- **Bar Chart**: Total sales per category.  

### **3. Performance Highlights**  
- **Treemap**: Top pizzas by sales (color = quantity).  
- **Top 3 Pizzas/Category**: Horizontal bar chart.  

### **4. Interactive Filters**  
- Filter by: `Pizza Category` | `Size` | `Date Range` *(if applicable)*.  


# FILES

### **Dataset Used**
- <a href="https://github.com/pragati-lad/PizzaDashboardProject/blob/main/pizza_sales.csv">`pizza_sales.csv`</a>

### **Visual Assets**
| Asset Type          | Preview/Link                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| **Dashboard ss**  | <a href="https://github.com/pragati-lad/PizzaDashboardProject/blob/main/dashboard_img.png">`dashboard.png`</a> |
| **PPT Background**  | <a href="https://github.com/pragati-lad/PizzaDashboardProject/blob/main/bkgd_ppt.pptx">`bg_ppt.jpg`</a> |
| **Dashboard BG img**    | <a href="https://github.com/pragati-lad/PizzaDashboardProject/blob/main/bkgd_img.jpg">`dashboard_bg.jpg`</a> |
