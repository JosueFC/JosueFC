# Josue Fernandez Canela

**Data Analyst · Analytics Engineer · Python & SQL**

Ph.D. in Plant Biology from the University of Georgia and M.S. in Analytics candidate at Texas A&M University. I bring a researcher's habits to business data: validate the data first, measure uncertainty honestly, and only claim what the evidence supports. I build the whole workflow, from ingestion and testing to models, dashboards and the business question at the end.

## Tech stack
- **Analysis:** Python (pandas, scikit-learn), SQL, R (tidyverse, ggplot2)
- **Data engineering:** dbt, DuckDB, BigQuery, PostgreSQL
- **BI & apps:** Power BI, Tableau, Streamlit
- **Engineering:** pytest, Git, GitHub Actions, FastAPI

## Featured projects

- **[Supplier trade-intelligence pipeline](https://github.com/JosueFC/trade-intelligence-pipeline)**: monthly ETL from the US Census trade API through DuckDB and dbt to a Streamlit dashboard showing which supplier countries are gaining or losing share.
  *Result:* idempotent, resumable loads guarded by 25 automated tests, including a check that country totals reconcile with the API's own totals.

- **[Bogotá Airbnb price benchmarking](https://github.com/JosueFC/bogota-airbnb-pricing)**: predicts a fair nightly price for 18,418 Bogotá listings and flags the ones priced far from comparable listings.
  *Result:* the random forest reaches 27% MAPE with whole hosts held out of training, against 31% for Lasso. A naive random split would have overstated its accuracy (23%).

- **[Page health score](https://github.com/JosueFC/page-health-score)**: a deterministic 0–100 SEO health score for any web page, built from its HTML, PageSpeed Insights and Search Console data.
  *Result:* 176 unit tests with every network call mocked, delivered through 7 pull requests.
