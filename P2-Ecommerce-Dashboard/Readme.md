# Project 2: E-Commerce Business Dashboard

## Overview
Analysis of 100,000 Brazilian e-commerce orders (2016-2018) from Olist 
to build an interactive self-service business dashboard answering 5 
key business questions.

## Status
Work in progress — Task 2 complete, Task 3 in progress

## Dataset
Brazilian E-Commerce Public Dataset by Olist (Kaggle)
5 related tables: orders, customers, payments, items, products
99,441 orders across 27 Brazilian states

## Tools
Python, pandas, plotly, SQLite, SQL, GitHub Pages

## Business Questions This Project Answers
1. What are the overall KPIs: total revenue, total orders, 
   average order value, return rate?
2. How does revenue grow month over month and what is the 
   percentage change?
3. Which product categories drive the most revenue?
4. Which customer geography contributes most to sales?
5. How do different customer segments compare on order value 
   and frequency?

## Tasks
- [x] Task 1: Data inspection — 5 tables loaded and analysed
- [x] Task 2: Data cleaning, merging and feature engineering
- [ ] Task 3: SQL analysis with CTEs and Window Functions
- [ ] Task 4: Interactive Plotly dashboard
- [ ] Task 5: Deploy to GitHub Pages
- [ ] Task 6: Executive summary and README final polish

## Key Findings So Far
- 99,441 orders across 2016 to 2018
- 2,965 orders never delivered to customers
- 775 orders have no item records
- master.csv created: 99,441 rows × 18 columns

## Files
- Notebooks/analysis.ipynb — full analysis notebook
- Data/Processed/master.csv — cleaned master DataFrame
- Outputs/ — charts and dashboard (coming in Task 4)