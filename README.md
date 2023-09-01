# B2B-Company
 B2B-Company-Analytics


Dataset taken from https://www.kaggle.com/datasets/nnthanh101/aws-saas-sales under license GNU Free, have amended some of the pricing, took an averge of the products products to set price for 2020, have added a 2.5% increase year over year, with an added 5% increase for 2023.

SCHEMAS/MODELING

One Big Table (OBT) - parquet file stored in AWS S2 bucket Denormalised Form - csv files kept locally on Github

Schemas have been loaded using the python dataframe libary Polars (https://www.pola.rs/), and OLAP databse Duckdb (https://duckdb.org/).

The Saas/B2B fictitious data set is aviable as a playground to test and learn exploratory data analysis (EDA), in the future I'd like to add Malloy (https://www.malloydata.dev/) and/or Ibis (https://ibis-project.org/) notebooks.

Virtual Environment: #!python -m venv venv #!source venv/bin/activate #! pip install -r requirements.txt