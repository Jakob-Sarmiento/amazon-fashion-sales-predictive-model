# Amazon Fashion Sales Predictive Model
---

## Project Goal
[Full Business Summary (PDF)](amazon_product_business_summary.pdf)

This project involves creating a predictive model using logistic regression.

The goal of this project is to pinnpoint the most important product features when it comes to product ratings.

---

## Preview of Key Findings 
- Category and brand have the highest influence on whether a product is highly rated or not.
--- 

## Business Strategies and Recommendations (Preview)

- **Pricing** - Sellers on Amazon should prioritize low to mid end prices, considering most fashion products are not high-end on Amazon, in terms of pricing.
- **Prioritization** - Companies selling bags should prioritize Amazon as one of their main channels, as bags are highly rated on Amazon.

---

## Visual Highlights

| Type of Visualization | Description |
|-----------------------|-------------|
| [Correlation Heatmap](images/correlation_heatmap_price_rating.png) | Minimal relationship between price and ratings |
| [Price Distribution Histogram](images/price_distribution.png) | Market dominated by low to mid-range pricing |
| [Ratings per Category Boxplot](images/rating_distribution_per_cat.png) | Most categories are rated between 4.0 and 5.0 stars |




## Data & Methods
- **Dataset** – Cleaned around 1,800 rows
- **Tools** – Python, Pandas, NumPy, Matplotlib, Seaborn.  
- **Notebook** – See [`03_amazon_fashion_sales_eda_analysis.ipynb`](03_amazon_fashion_eda.ipynb) for full EDA workflow.

---

## Next Steps
- **Track exact numbers** – Extract KPIs including category growth rates, review volumes, and price–rating relationships to measure the trends discovered in the initial EDA.  
- **E-commerce platform comparison** – Perform EDA on other e-commerce platforms to compare category and product performance.
