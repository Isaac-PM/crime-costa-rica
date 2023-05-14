# Analysis of crime data in Costa Rica: years 2020 to 2022

<img src="https://upload.wikimedia.org/wikipedia/commons/7/7b/Polic%C3%ADa_resguarda_Asamblea_Legislativa_de_Costa_Rica_1_de_mayo_2013.JPG" width="640px">

# Abstract

This side project focuses on the collection, filtering, storage, and analysis of data related to crime in Costa Rica.

The main objectives of this analysis phase are as follows:

- Clean and filter the data, in order to store it in a database. <img src="https://img.shields.io/badge/-done-green">
- Provide a basic statistical representation through graphs. <img src="https://img.shields.io/badge/-working%20on-yellow">
- Visualize the data in various ways on the map of Costa Rica.
- Use this data to train a Deep Learning model.

# Data sources

## Territorial administrative distribution

Registro Nacional, Instituto Geográfico Nacional. (2021). _Totales de provincias, cantones y distritos de Costa Rica._ Retrieved from: https://files.snitcr.go.cr/boletines/DTA-TABLA%20POR%20PROVINCIA-CANT%C3%93N-DISTRITO%202022V3.xlsx

## Crime records

Justicia Abierta Costa Rica. (2022). _Estadísticas policiales 2022_. Retrieved from: http://datosabiertospj.eastus.cloudapp.azure.com/tr/dataset/estadisticas-policiales/resource/34843f7c-fc4a-4132-a36a-a5d9d232cd5a

Justicia Abierta Costa Rica. (2021). _Estadísticas policiales 2021_. Retrieved from: http://datosabiertospj.eastus.cloudapp.azure.com/tr/dataset/estadisticas-policiales/resource/0435fa53-a3c1-4ef0-afac-5d8be27a2777

Justicia Abierta Costa Rica. (2020). _Estadísticas policiales 2020_. Retrieved from: http://datosabiertospj.eastus.cloudapp.azure.com/tr/dataset/estadisticas-policiales/resource/7154752f-a00a-4ed9-be9f-6c506ac33910

## KML polygons according to administrative territorial distribution

Moritz von Schweinitz. (2020). _CR_distritos_geojson_. Retrieved from: https://github.com/schweini/CR_distritos_geojson/tree/master

# References

Folium documentation. (2023). _Quickstart_. Retrieved from: https://python-visualization.github.io/folium/quickstart.html#Getting-Started

Plotly documentation. (s.f.). _Mapbox Choropleth Maps in Python_. Retrieved from: https://plotly.com/python/mapbox-county-choropleth/

deparkes. (2016). _Folium Map Tiles_. Retrieved from: https://deparkes.co.uk/2016/06/10/folium-map-tiles/

notebook.community. (s.f.). _Using folium.colormap_. Retrieved from: https://notebook.community/BibMartin/folium/examples/Colormaps

Data to Fish. (2023). _How to Import a CSV File into Python using Pandas_. Retrieved from: https://datatofish.com/import-csv-file-python-using-pandas/

# Libraries (Python 3.11.2)

- `branca`
- `jinja2`
- `requests`
- `sqlite3`
- `unidecode`: [Unidecode 1.3.6](https://pypi.org/project/Unidecode/)
- `folium`: [folium 0.14.0](https://python-visualization.github.io/folium/)
- `kml2geojson`: [kml2geojson 5.1.0](https://pypi.org/project/kml2geojson/)
- `pandas`: [pandas 2.0.1](https://pandas.pydata.org/)
- `SQLAlchemy`: [SQLAlchemy 2.0.12](https://www.sqlalchemy.org/)

# Cleaned dataset

Isaac PM. (2023). _Crime data in Costa Rica: years 2020 to 2022._ Retrieved from: https://www.kaggle.com/datasets/isaacpm21/crime-data-in-costa-rica-years-2020-to-2022
