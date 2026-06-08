!pip install geopandas
import folium
import geopandas as gpd

from folium.plugins import (
    MarkerCluster,
    HeatMap,
    MeasureControl
)
folium.GeoJson(
    ubs,
    name='ubs'
).add_to(m)
