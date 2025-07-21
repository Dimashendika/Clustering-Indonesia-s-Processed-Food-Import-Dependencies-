### Objective

To analyze Indonesia’s import trends of processed food and agro-products from 2013 to 2023, identify top-performing and declining products using CAGR analysis, and apply K-Means clustering to segment products based on growth potential and import value — providing insights for strategic procurement or trade policy decisions.

---

### Dataset

* Source: International Trade Centre (ITC Trade Map)

* Reporter: Indonesia

* Partner: World

* Product Group: Processed food and agro-products (e.g. wheat flour, milk, sauces, etc)

* Period: 2013–2023

* Value Unit: USD Thousand (i.e., all import values are in thousands of US dollars)  

* Format: Excel

* Link: https://www.trademap.org/Index.aspx?nvpm=1%7c%7c%7c%7c%7c%7c%7c%7c%7c%7c%7c%7c%7c%7c%7c%7c%7c

---

##  Tools & Libraries
- `Python`
- `Pandas`,
- `Matplotlib`,
- `Seaborn`
- `statsmodels` (for ARIMA forecasting)
- `Jupyter Notebook`

##  Key Insights from Clustering Results

Based on the clustering results using **CAGR** (2013–2023) and **Import Value in 2023**, the products were grouped into 3 distinct clusters. The table below summarizes the characteristics of each cluster:

| Cluster | Number of Products | Avg. CAGR (2013–2023) | Avg. Import Value 2023 (Thousand USD) | Characteristics                                                        |
|---------|--------------------|------------------------|-------------------------------|-------------------------------------------------------------------------|
| 0       | 272 products        | +5.7% (moderate)       | ~25,900                       | General products with low to mid import volumes and mixed growth        |
| 1       | 41 products         | -99.0% (very low)      | ~0.17                         | Sunset products with extremely negative growth and near-zero imports    |
| 2       | 3 products          | +11.9% (high)          | ~2,400,000                    | Strategic high value products with strong and consistent growth         |



---

###  Cluster 0 – General / Low-Mid Value Products
- Largest group (272 products).
- Moderate growth rate (+5.7% CAGR).
- Import values are relatively small.

###  Cluster 1 – Sunset Products (Obsolete)
- Very steep negative CAGR (around −99%).
- Average import value close to **zero**.
- Likely phased out due to regulatory shifts, local substitutions, or reduced demand.

###  Cluster 2 – Strategic & High-Value Imports
- Smallest group (3 products), but extremely **high import value** (avg. ~$2.4M).
- High and positive CAGR (+11.9%).
- Critical to monitor for cost efficiency, supply stability, or import substitution strategies.

---

##  Business Implications

- **Cluster 2** should be prioritized for strategic sourcing, import cost optimization, or potential local production initiatives.
- **Cluster 0** offers opportunities for rationalization through bundling, warehouse optimization, or supplier management.
- **Cluster 1** includes products with declining relevance — these may be discontinued or ignored in future import plans.
