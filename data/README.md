# Data Access Instructions

This project uses publicly available datasets from the World Bank API (2015) for:

- GDP per capita: `NY.GDP.PCAP.CD`
- Literacy rate: `SE.ADT.LITR.ZS`
- Crime rate (homicides per 100,000): `VC.IHR.PSRC.P5`

All datasets used in this project consist of 45 observations (countries) with complete data for 2015.

To access these datasets:

1. Visit [World Bank Open Data](https://data.worldbank.org/)
2. Use the indicators listed above to locate the data
3. Alternatively, you can replicate data collection using R and the `httr` + `jsonlite` packages as demonstrated in `index.Rmd`

No raw data files are included in this repo due to API sourcing.
