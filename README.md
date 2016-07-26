# Geocoded RNI Activities in GeoJSON
This repository contains a data folder with a complete list of geocoded activities that were completed as part of [Ushahidi](https://www.ushahidi.com)'s [Resilience Network Initiative](http://cityresilience.net/what-is-rni.html)("RNI"). All data were pulled from the [Ushahidi deployment for the Resilience Network Initiative](http://rni.ushahidi.com/) and are presented in the original .csv download format but have also been converted to GeoJSON. 

The [data folder](https://github.com/Shadrock/RNI-Activity-Map/tree/master/Data) contains:
* A polygon to denote the [boundaries of the neighborhood of Purwodinatan] (Data/Purwodinatan%20Neighborhood%20Project%20Area.geojson), which was the focus of our work in Semarang, Indonesia. You can learn more about that project [in this video](https://vimeo.com/129603769) and [this blog post](http://www.100resilientcities.org/blog/entry/kathmandu-semarang-citizen-engagement-and-open-data-mapping-in-two-cities#/-_/).
* A complete [list of all activities](Data/RNI_activities_2013-2015.geojson) conducted as part of RNI in GeoJSON. 
* A complete [list of all activities](https://github.com/Shadrock/RNI-Activity-Map/blob/master/Data/RNI_download_20160603.csv) conducted as part of RNI in a table... for those who like that sort of thing. 

[GeoJSON](http://geojson.org/) is a great open standard format designed for representing simple geographical features, which also allows for [data to be previewed as a map via Github](https://help.github.com/articles/mapping-geojson-files-on-github/). Because Ushahidi deployments commonly offer .csv as a download default, I used [this tool] (http://www.convertcsv.com/csv-to-geojson.htm) to convert .csv to GeoJSON. Mapbox also offers a [handy tool](http://mapbox.github.io/togeojson/) for converting .gpx files to GeoJSON.



