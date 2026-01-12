# London-Residential-Market-Report-2026

London Residential Market Report 2026.pdf contains the full presentation report. 

The data source is not uploaded in this respositary. It is available from the link below.
https://www.gov.uk/government/statistical-data-sets/price-paid-data-downloads

Data Preparation.ipynb contains Python codes that load the dataset into a dataframe,filter data and format data.

London Property Price Data Visualisation.ipynb contains Python codes that do data refinement, statistical modeling and data visualization.

The rest of the png files are the charts and dashboard created through the process.

Methodology of the analysis

Primary Source: HM Land Registry Price Paid Data (1995–2025).

Compliance: Contains HM Land Registry data © Crown copyright and database right 2021. This data is licensed under the Open Government Licence v3.0.

Acquisition: Leveraged Python (Pandas) to extract and aggregate a longitudinal dataset covering 30 years of transaction history.

Wrangling: Utilized Python (Pandas) to standardize temporal formats, map categorical codes (e.g., Tenure, Property Type) to descriptive attributes, and implement logic for handling missing data.

Refinement: Programmed a custom filtering script in Python to enforce a "Residential-Only" constraint (Categories D, S, T, F), programmatically isolating relevant market data from commercial and industrial noise.

Statistical Modeling: Leveraged Python (Pandas) for multi-level aggregation, price distribution modeling, and outlier detection.

Visualization: Designed high-fidelity charts and Dashboards using Python (Matplotlib & Seaborn), employing log-scaling and sampling techniques for clear visual storytelling.

