# Corporate Tax Transparency Geospatial Analysis
This notebook produces choropleth map visualisations for the total income earned, total taxable income and total tax payable for businesses with ABNs (Australian Business Numbers).

This is a larger project encompassing the use of Python libraries such as Folium, as well as outputs from other relevant data pipelines. The pipelines are as follows:
- [ABN Postcode Extractor](https://github.com/hbbymth42/abn_postcode_extractor) - Used to extract Postcode information from the Australian Business Register's [ABN bulk extract](https://data.gov.au/data/dataset/abn-bulk-extract).
- [ASGS Geonames Data Pipeline](https://github.com/hbbymth42/asgs_geonames_pipeline) - Used to create Shapefiles for use with [GeoPandas](https://geopandas.org/en/stable/index.html) and for visualisation with [Folium](https://python-visualization.github.io/folium/latest/index.html). Data sourced from [GeoNames](https://www.geonames.org/) and the [ASGS](https://www.abs.gov.au/statistics/standards/australian-statistical-geography-standard-asgs-edition-3/jul2021-jun2026/access-and-downloads/digital-boundary-files).

The data used for analysis was the Australian Tax Office's [2021-22 Corporate Tax Transparency Report](https://data.gov.au/data/dataset/corporate-transparency).

Conda is required to create the environment to run this notebook with the appropriate packages. Read more into installing conda [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html).
