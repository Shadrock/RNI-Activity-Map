# Geocoded RNI Activities in GeoJSON
This repository contains a data folder with a complete list of geocoded activities that were conducted as part of [Ushahidi](https://www.ushahidi.com)'s [Resilience Network Initiative](http://cityresilience.net/what-is-rni.html) ("RNI") in GeoJSON. [GeoJSON](http://geojson.org/) is a great open standard format designed for representing simple geographical features, which also allows for [data to be previewed as a map via Github](https://help.github.com/articles/mapping-geojson-files-on-github/). 

##Data
The [data folder](https://github.com/Shadrock/RNI-Activity-Map/tree/master/Data) contains:
* A polygon to denote the [boundaries of the neighborhood of Purwodinatan] (Data/Purwodinatan%20Neighborhood%20Project%20Area.geojson), which was the focus of our work in Semarang, Indonesia. You can learn more about that project [in this video](https://vimeo.com/129603769) and [this blog post](http://www.100resilientcities.org/blog/entry/kathmandu-semarang-citizen-engagement-and-open-data-mapping-in-two-cities#/-_/).
* A complete [list of all activities](Data/RNI_activities_2013-2015.geojson) conducted as part of RNI in GeoJSON. 
* A complete [list of all activities](Data/RNI_download_20160811.csv) conducted as part of RNI in a table... for those who like that sort of thing. 

Note that each record contains a field labeled "Geo Precision Code." The number provided corresponds to the [International Aid Transparency Initiative's (IATI) geographical precision standard](http://iatistandard.org/202/codelists/GeographicalPrecision/), which clarifies the accuracy and usage of geographical coordinates.

## Steps for Converting Data
The following steps were taken to convert data from an Ushahidi deployment (version 2) for this repository.

1. Downloaded data from the [Ushahidi deployment](http://rni.ushahidi.com).
2. Previewed data and corrected diacritical marks and other typographic symbols that did not display correctly in a spreadsheet editor. Also added the geographic precision code, which is part of a custom form in the Ushahidi deployment that did not automatically appear in the report download. 
3. Because older Ushahidi deployments commonly offer .csv as a download default, I used [this tool] (http://www.convertcsv.com/csv-to-geojson.htm) to convert .csv to GeoJSON.
4. Previewed and cleaned up resultant code with [Mapbox's](https://www.mapbox.com/) [geojson.io](http://geojson.io), which also allowed me to...
5. save code directly to Github. 

Additionally, Mapbox has another [handy tool](http://mapbox.github.io/togeojson/) for converting .gpx files to GeoJSON.


