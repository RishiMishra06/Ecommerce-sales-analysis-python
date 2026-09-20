# E-Commerce Sales Analysis (Python)

An exploratory data analysis project on retail sales data — done in Python using Pandas, Matplotlib, and Seaborn. I picked this up to practice real EDA workflows: cleaning data, grouping/aggregating with pandas, and building clear visualizations to answer specific business questions.

![Total Sales by Category](category_sales_with_labels.png)

## About this project

The dataset covers **9,994 orders** from 2014 to 2017 across the US, with sales, profit, quantity, and discount info broken down by category, sub-category, customer segment, and region. I worked through it question by question — starting with basic monthly trends and going deeper into profitability by category and segment.

## Tools I used

- Python (Pandas, NumPy)
- Matplotlib & Seaborn for visualizations
- Jupyter Notebook

## Questions I answered

1. Which month had the highest and lowest sales overall?
2. Which product category has the highest vs lowest sales?
3. How do sales break down by sub-category?
4. Which month had the highest profit?
5. Which sub-category is most/least profitable?
6. How do sales, profit, and profit margin compare across customer segments?
7. What's the sales-to-profit ratio for each category?

## Key findings

- **November had the highest total sales** (₹352,461) across all years combined, while **February was consistently the weakest month** (₹59,751) — a pattern that shows up almost every year in the data.
- **Technology leads in total sales** (₹836K), narrowly ahead of Furniture (₹742K) and Office Supplies (₹719K).
- **Phones and Chairs are the top-selling sub-categories** by revenue, but that doesn't translate to the most profit — **Copiers, Phones, and Accessories are actually the most profitable sub-categories**.
- **Tables are a problem area** — they generate solid sales but end up **-₹17,725 in losses**, the worst of any sub-category. Bookcases and Supplies are also mildly unprofitable.
- **Furniture has a sales-to-profit ratio of 40.21**, way higher than Office Supplies (5.87) and Technology (5.75) — meaning Furniture sales don't convert to profit nearly as efficiently as the other two categories, likely due to heavy discounting on big-ticket items like tables.
- **Consumer segment drives the most revenue** (₹1.16M) but **Home Office customers have the best profit margin** (14.03%) compared to Consumer (11.55%) and Corporate (13.03%) — smaller segment, but more efficient.
- December edges out November slightly for the single highest profit month (₹43,369), even though November wins on raw sales — discounting patterns likely explain the gap.

## What's in this repo

```
├── ECommerce_Sales_Python_Project.ipynb      # full analysis notebook
├── ECommerce_Sales_Python_Project.pdf        # exported notebook (view without Jupyter)
├── Sample_-_Superstore_XL_Data.csv           # dataset used
├── category_sales_with_labels.png
├── monthly_sales_by_year.png
├── total_monthly_sales_all_years.png
├── monthly_profit_chart.png
├── sub_category_sales_chart.png
├── profit_by_category_subcategory.png
├── segment_sales_profit.png
├── sales_profit_by_segment_combined.png
├── sales_to_profit_ratio_by_category.png
└── README.md
```

## Dataset

Used the well-known **Sample Superstore** dataset — a US-based retail dataset with order-level detail across Furniture, Office Supplies, and Technology categories, commonly used for practicing sales/profit analysis.

## How to run it

1. Clone this repo
2. Install dependencies: `pip install pandas numpy matplotlib seaborn`
3. Open `ECommerce_Sales_Python_Project.ipynb` in Jupyter and run all cells

## Author

Rishi Mishra
