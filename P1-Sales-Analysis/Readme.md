# Project 1: Superstore Sales Performance Analysis

## Overview
Analysis of 4 years of retail sales data (9,994 orders) to identify 
profit drivers, regional gaps, and discount inefficiencies.

## Tools Used
Python, pandas, matplotlib, plotly, SQLite, SQL

## Business Questions Answered
1. Which product categories and sub-categories generate the most profit?
2. Which regions are underperforming and what is the root cause?
3. What is the monthly revenue trend over the full date range?
4. Which customer segments have the worst discount-to-profit ratio?
5. What are the top 10 and bottom 10 products by profit margin?

## Key Findings
- Technology drives profitability (Copiers at 31.72% margin); Tables 
  and Bookcases generate consistent losses across all years.
- Central region over-discounts at 24% average, more than double 
  West's 10.9%, resulting in the lowest profit despite high sales volume.
- Strong Q4 seasonality every year; January and February are 
  consistently weakest.
- Consumer segment has highest volume but lowest margin (11.20%); 
  Home Office is most efficient at 14.29%.
- Revenue grew 51% from 2014 to 2017.

## Live Dashboard
[View interactive dashboard](https://gyan-sutra.github.io/data-analyst-portfolio/P1-Sales-Analysis/Outputs/dashboard.html)

## Files
- `Notebooks/sales_analysis.ipynb` — full analysis notebook
- `Outputs/sales_analysis_4panel.png` — summary chart
- `Outputs/extended_analysis.png` — seasonality and yearly growth charts
- `Outputs/dashboard.html` — interactive plotly dashboard