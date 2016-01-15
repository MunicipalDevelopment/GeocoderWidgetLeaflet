# Geocoder Widget for Leaflet
The geocoder widget for leaflet adds a textbox in the center of your map.
![image](https://raw.githubusercontent.com/MunicipalDevelopment/GeocoderWidgetLeaflet/master/geocoder.JPG)

This repository has 2 version:
* geocoderMap.js: This version works with geocoderMap.html. It only requires you to link to geocoder.css and script src the geocoderMap.js file. Everything will be handled by the addin.
* geocoderMapClass: This works with geocoderMapClass.html. It requires linking the css and js, but also adds the need to call `new geocoder()` or specify a geocoder `var g = new geocoder("http://coagisweb.cabq.gov/arcgis/rest/services/locators/CABQ_Composite/GeocodeServer/findAddressCandidates");` This means you can use the addin in an locale that has a public ESRI REST Geocoding service.
