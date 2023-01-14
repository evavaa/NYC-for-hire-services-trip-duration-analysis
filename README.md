# MAST30034 Project 1 README.md

## README
**Research Goal:** Analysis and forecasting of trip duration for High
Volume For-hire Services in NYC

**Timeline:** The timeline for the research area is 02/2019 - 07/2019 Inclusive.

To run the pipeline, please visit the `notebooks` directory and run the files in order:
1. `download.ipynb`: This downloads the raw data into the `data/raw` directory.
2. `preprocess.ipynb`: This notebook details all preprocessing steps and outputs it to the `data/curated` directory.
3. `analysis.ipynb`: This notebook is used to conduct analysis and visualisations on the curated data.
4. `modelling.ipynb`: The notebook is used to conduct hyperparameter tuning and run the model.

**External Dataset:** The external data is downloaded from the Weather Underground (https://www.wunderground.com/history/monthly/us/ny/new-york-city) and stored in `data/raw/weather_data` directory.
