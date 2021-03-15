# Player Heat Map
Notebooks for creating player heat maps

## Setting Up
Run

```pip install -r requirements.txt```

Instructions for gmaps: https://jupyter-gmaps.readthedocs.io/en/latest/install.html#installing-jupyter-gmaps-with-pip

Installing Jupyter: https://jupyter.org/install

A widget error occurred when running in JupyterLab, but the normal Jupyter Notebook was able to display correctly

A Google API Key is needed: https://developers.google.com/maps/documentation/geocoding/get-api-key

Create a `.env` file based on `.env.example`, inserting your Google API Key.

## player-get-lat-long.ipynb
This fetches the lat/long geocodes for all players in `assets/liu-player-data.csv` (this is a csv copy of the `Player History Master List` Google Sheet).
The updated csv will be wrote to `assets/liu-player-data-lat-long.csv`.

## player-heat-map.ipynb
This draws the heat map.
