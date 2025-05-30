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

## Packed Bubble Chart:               
Shows pizza quantity by name/size.
Bubble size = order volume; color = pizza size.

## Sales Distribution: 
Pie Chart: % revenue by category.
Bar Chart: Total sales per category.

## Performance Highlights: 
Treemap: Top pizzas by sales (weighted + color-coded by quantity).
Top 3 Pizzas/Category: Horizontal bar chart.

## Interactive Filters: 
Dynamic filtering by pizza category.


