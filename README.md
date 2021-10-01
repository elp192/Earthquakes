## Project Overview
In this project, an interactive map representing earthquakes around the world is created. The earthquakes' magnitudes and coordinates are obtained from GeoJSON data, and data is plotted on Mapbox map via an API call.

The following sources and tools are utilized:<br>
GeoJSON file:
- [Tectinic Plates](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json)
- [Earthquakes data related to past 7 days](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson)
- [Major Earthquakes (above 4.5 mag) data related to past 7 days](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson)

Languages: Javascript, HTML, and CSS

Dependencies: Leaftlet and D3.js

Software: Visual Studio Code

API: [Mapbox account](https://www.mapbox.com) is created and Mapbox API key is saved in the config.js file in /earthquakes/static/js/.

## Results
The final files to create the following results are store in earthquakes folder Earthquakes/earthquakes/
<p img align="center" width="100%">
<img width="600" alt="streets" src="https://user-images.githubusercontent.com/85843401/135540412-acdf0df1-1e56-4f7d-9a48-696e00801532.png">
<figcaption>Figure 1: An interactive map: street view.</figcaption></figure/> 
<p align="center">
</p>


<p img align="center" width="100%">
<img width="600" alt="satellite" src="https://user-images.githubusercontent.com/85843401/135540420-9ff13492-a3cb-49d6-a98a-c600cf4ef04d.png">
<figcaption>Figure 2: An interactive map: satellite view.</figcaption></figure/> 
<p align="center">
</p>


<p img align="center" width="100%">
<img width="600" alt="dark" src="https://user-images.githubusercontent.com/85843401/135540431-5db06f51-2078-44c1-8457-db68b0e73e39.png">
<figcaption>Figure 3: An ineractive map: dark view.</figcaption></figure/> 
<p align="center">
</p>

