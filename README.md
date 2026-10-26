# POWER BI SALES PERFORMANCE DASHBOARD
Assignment 2 - Clothing Sales Analysis

### PROJECT FOLDER CONTAINING:

1. Power BI File (.pbix)
The Power BI file includes:
- Data model created in Assignment 1
- All calculated columns
- All DAX measures
- Completed visualizations
- Proper formatting and labels

2. PDF Document
Include screenshots of:
- DAX formulas used
- Created visualizations
- Dashboard layout
- Provide a brief explanation for each visual.

---

CALCULATED COLUMNS (3):
1. Category Type = 'Order Details'[Category] & " - " & 'Order Details'[Sub-Category]
2. Revenue per Order = 'Order Details'[Amount] * 'Order Details'[Quantity]
3. Sales Category = IF('Order Details'[Amount] > AVERAGE('Order Details'[Amount]), "Above Average", "Below Average")

DAX MEASURES (4):
1. Total Sales = SUM('Order Details'[Amount])
2. Total Target = SUM('Target'[Target])
3. Order Count = COUNTROWS('Order Details')
4. Achievement % = DIVIDE([Total Sales], [Total Target], 0)

VISUALIZATIONS (6):
1. Sales Overview by Category
2. Regional Sales Performance
3. Customer Segment Distribution
4. Sales Performance Matrix
5. Sales Distribution by Sub-Category (Treemap)
6. Order Count by State

EXPLANATIONS:
1. Sales Overview - Shows total sales per category
2. Regional Performance - Shows sales by region
3. Customer Segment - Shows customers by segment
4. Performance Matrix - Monthly Target vs Actual
5. Treemap - Sales by Sub-Category (Saree)
6. Order Count - Orders by State

TITLE: CLOTHING SALES PERFORMANCE DASHBOARD# Power-BI-Data-Visualization
