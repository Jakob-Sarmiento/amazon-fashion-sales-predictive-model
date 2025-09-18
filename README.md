# Amazon Fashion Sales Predictive Model
---

## Project Goal
[Full Business Summary (PDF)](04_amazon_predictive_model_business_summary.pdf)

This project involves creating a predictive model using logistic regression.

The goal of this project is to pinnpoint the most important product features when it comes to product ratings.

---

## Preview of Key Findings 

- Category and brand have the highest influence on whether a product is highly rated or not.
--- 

## Business Recommendations (Preview)

- Sellers on Amazon should prioritize selling their products in highly rated categories, i.e "Sportswear", to maximize their chances of reaching the highest sales.
  
- Although pricing may be a factor for companies and deciding their profits, higher/lower pricing doesn't automatically lead to more product sales.

---

## Model Visualizations

| Visualization | Description |
|-----------------------|-------------|
| [Confusion Matrix](images/correlation_heatmap_price_rating.png) | Model |
| [Roc Curve Plot](images/price_distribution.png) | Market dominated by low to mid-range pricing |
|

## Tools Used
- **Dataset** – Cleaned around 1,800 rows
- **Tools** – Python, Pandas, NumPy, Matplotlib, Seaborn.  
- **Notebook** – See [`03_amazon_fashion_sales_eda_analysis.ipynb`](03_amazon_fashion_eda.ipynb) for full EDA workflow.

---

## Next Steps
- **Track exact numbers** – Extract KPIs including category growth rates, review volumes, and price–rating relationships to measure the trends discovered in the initial EDA.  
- **E-commerce platform comparison** – Perform EDA on other e-commerce platforms to compare category and product performance.
