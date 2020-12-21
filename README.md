# urban-ag-DC
Urban farms and garden projects in Washington, DC

## About 
I think farming in cities is not only super cool, but is the stuff of food security (or at least nutrition security) now and in the future. Thankfully, planners and staff in Washington DC have pulled together some very nice data which I can turn into a pretty map in MapBox which looks at current sites of urban agriculture. 

## Data sources 
Data for this map comes from shapefiles provided by the District Department of Transportation (DDOT) Urban Forestry division in Washington, DC. 
* [Urban agriculture polygons](https://urban-forestry-dcgis.opendata.arcgis.com/datasets/urban-agriculture-areas-polygons)
    Urban agriculture sites often have a commercial focus, and differ from community garden spaces in that they are not for public use. The Urban Agriculture polygons were drawn by Office of Planning staff using satellite imagery, and calculated total acreages often differ from the farm's self-reported acreages. It's recommended that this data is used internally only; however, it provides an interesting contrast in the map to garden spaces for public use only, and demonstrates the fairly singificant number of urban agricultural products produces in Washington, DC. 

* [Community garden polygons](https://urban-forestry-dcgis.opendata.arcgis.com/datasets/community-gardens-polygons)
    Community gardens in DC are inteded for use by the public, and are organized via 1. DC Department of Parks and Recreation (DPR); 2. National Parks Service (NPS); or 3. independent organizations.

* [School garden points](https://urban-forestry-dcgis.opendata.arcgis.com/datasets/school-gardens)
    School garden data is self-reported and collected annually by the Office of the State Superintendent of Education (OSSE) as part of the School Health Profiles created under the Healthy School Act. 

Bus stop points from OpenStreetMapwere were added to QGIS 3.14, and the geojson added to MapBox as a tileset.

GitHub Pages [Link](https://chels-map.github.io/urban-ag-DC/)

<!--It's quite wordy with all the labels and layers on at the same time, is there a clever way to toggle the layers/a feature that can be added to the MapBox legend? Or should I format the different layers to come in at different zoom levels to prioritize? what do you think about the color scheme?

What kind of analysis might be useful for people who live in DC which may see this map? Not Points of Interest like maybe for a tourist, because these gardens are not for the transient public but to serve the communities of place, the place being washington DC.-->