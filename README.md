# Josue Fernandez Canela

Data analyst and analytics engineer. I build the pipeline, test the data, then answer the business question on top of it.

**Stack:** Python (pandas, scikit-learn) · SQL (BigQuery, DuckDB) · dbt · R (tidyverse, ggplot2) · Power BI · Tableau · Streamlit · pytest · GitHub Actions

## Selected projects

**[Supplier trade-intelligence pipeline](https://github.com/JosueFC/trade-intelligence-pipeline)**
Monthly ETL from the US Census trade API through DuckDB and dbt to a Streamlit dashboard showing which supplier countries are gaining or losing share.
*Result:* idempotent, resumable loads guarded by 25 automated tests, including a check that country totals reconcile with the API's own totals.

**[Bogotá Airbnb price benchmarking](https://github.com/JosueFC/bogota-airbnb-pricing)**
Predicts a fair nightly price for 18,418 Bogotá listings and flags the ones priced far from comparable listings.
*Result:* the random forest reaches 27% MAPE with whole hosts held out of training, against 31% for Lasso. A naive random split would have overstated its accuracy (23%).

**[Page health score](https://github.com/JosueFC/page-health-score)**
A deterministic 0–100 SEO health score for any web page, built from its HTML, PageSpeed Insights and Search Console data.
*Result:* 173 unit tests with every network call mocked, delivered through 7 pull requests.
