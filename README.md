# Superstore Sales & Discount Impact Analysis

## Problem Statement
Retail teams often increase discounts to drive higher sales volume, assuming revenue growth will translate into higher profit. This project evaluates whether aggressive discounting actually improves profitability or destroys margin across product categories.

## Dataset Overview
- ~9,900 retail transactions  
- Categories: Furniture, Office Supplies, Technology  
- Key variables: Sales, Profit, Discount, Order Date, Region  

## Key Business Questions
- Is revenue growth translating into profit growth?
- At what discount level does profitability turn negative?
- Which product categories contribute the highest losses under high discounting?

## Key Insights
- Discounts **below 30%** are consistently profitable across all categories.
- Discounts **≥30% lead to net losses**, despite higher order volume.
- Office Supplies and Technology contribute the **highest absolute losses** at high discount levels.
- Increased sales volume at high discounts **fails to offset margin erosion**, indicating poor unit economics.

## Business Recommendations
- Cap standard discounts at **20–25%** across all categories to protect margins.
- Use discounts **≥30% only for clearance or customer acquisition**, not revenue growth.
- Prioritize **pricing optimization, bundling, and cross-sell strategies** instead of blanket discounting.

## Tools Used
Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook
