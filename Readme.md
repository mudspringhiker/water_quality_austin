## Exploration of Water Quality Data for Austin, TX

The data for this analysis is available [here](https://data.austintexas.gov/Environmental/Water-Quality-Sampling-Data/5tye-7ray).

Information on the features can be obtained [here](https://data.austintexas.gov/api/views/5tye-7ray/files/KtRsxGFDIvadsBKG4x5j9-qg56MXvotF5jOymfi_k6Y?download=true&filename=City%20of%20Austin%20Water%20Quality%20Sampling%20Data.pdf). But this notebook focuses on the following:

- watershed
- sample_date
- site_name
- result
- unit (it turns out that the data were obtained using different methods to measure a particular parameter)
- lon_dd_wgs84
- lat_dd_wgs84

Looking at the notebook was helpful in understanding the data and gave clues on how to scrape it from the Austin, TX Open Data Portal.

A Flask app that depends on the analysis done in this repo has been created and deployed at https://waterqualityatx.herokuapp.com/. The repo for the flask app is found at https://github.com/mudspringhiker/waterATX2018.

