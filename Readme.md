## Exploration of Water Quality Data for Austin, TX

The data for this analysis is available [here](https://data.austintexas.gov/Environmental/Water-Quality-Sampling-Data/5tye-7ray).

The data used for the notebook were downloaded on Jan 27, 2017.

Information on the features can be obtained [here](https://data.austintexas.gov/api/views/5tye-7ray/files/KtRsxGFDIvadsBKG4x5j9-qg56MXvotF5jOymfi_k6Y?download=true&filename=City%20of%20Austin%20Water%20Quality%20Sampling%20Data.pdf). But this notebook focuses on the following:

- watershed
- sample_date
- site_name
- result
- unit (it turns out that the data were obtained using different methods to measure a particular parameter)
- lon_dd_wgs84
- lat_dd_wgs84

Looking at the notebook was helpful in understanding the data and gave clues on how to scrape it from the web.

This [repo](https://github.com/mudspringhiker/waterqualityAUS) contains the code for the flask webapp that scrapes only the E.coli results (unit is MPN/100mL). This web app is deployed at [https://immense-hamlet-63542.herokuapp.com/](https://immense-hamlet-63542.herokuapp.com/).

