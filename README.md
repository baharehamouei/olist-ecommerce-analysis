# Olist E-Commerce Performance Analysis
**Tools:** Excel · SQL (SQLite) · Power BI  
**Dataset:** Olist Brazilian E-Commerce — 99,441 orders (Kaggle)  
**Duration:** 2 days  
**Status:** Completed ✅

## Project Overview
Olist is Brazil's largest e-commerce marketplace, connecting small businesses 
to major sales channels. This project analyzes nearly 100,000 real orders 
to uncover revenue patterns, delivery bottlenecks, and customer satisfaction 
drivers across Brazil's 27 states — simulating the day-to-day analytical 
work of a business analyst in an e-commerce company.

## Business Questions Answered
1. Which product categories generate the most revenue?
2. Which Brazilian states place the most orders?
3. What is the average delivery time and which states are slowest?
4. Does faster delivery lead to better customer reviews?
5. How did monthly revenue grow over 2017–2018?
6. Which sellers generate the most revenue?
7. What payment methods do customers prefer?
8. Which states have the highest shipping costs?

## Key Findings
- Health & Beauty is the #1 revenue category with 1.26M BRL in sales,
  followed by Watches & Gifts at 1.21M BRL
- São Paulo accounts for 40,501 orders — 42% of all deliveries nationwide
- Average delivery time is 12.5 days, but remote northern states like 
  Roraima and Amapá average over 28 days
- There is a clear correlation between delivery speed and satisfaction: 
  fast deliveries (under 7 days) score 4.4/5 in reviews, while very slow 
  deliveries (21+ days) drop to 3.1/5
- Revenue grew consistently from 350K BRL/month in early 2017 to over 
  1M BRL/month by mid-2018 — nearly 3x growth in 18 months
- Credit card dominates at 73.9% of all transactions
- Northern and northeastern states pay up to 40 BRL more in shipping 
  costs, explaining both slower delivery times and lower order volumes

## Process
1. **Excel** — imported raw CSV files, filtered to 96,478 delivered orders, 
   calculated delivery days using date formulas
2. **SQL (SQLite)** — wrote 8 queries joining 5 tables to extract 
   business insights by category, state, seller, and time period
3. **Power BI** — built a 2-page interactive dashboard with 8 visuals 
   and 3 KPI cards

## Dashboard Preview
See full dashboard in `Project1_Olist_Analysis_Bahareh_Amouei.pdf`

## Files
| File | Description |
|------|-------------|
| `Project1_Olist_Analysis_Bahareh_Amouei.pdf` | Power BI dashboard export |
| `Olist_Dashboard_Bahareh.pbix` | Power BI source file |
| `olist_orders_clean.xlsx` | Cleaned orders data |
| `results_*.csv` | SQL query outputs |

## Data Source
[Olist Brazilian E-Commerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) — Kaggle
