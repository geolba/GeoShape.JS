# GeoShape.JS
Javascript converter from geoJSON to ESRI shapefile (Miroslav Janata, mirajanata@volny.cz)


# Usage
1. Download the project files

2. Reference the source javascript files in your web page:

... [html]
    <script src="js/jszip.js"></script>
    <script src="js/GeoShape.js"></script>
...

Alternatively you can use more browser compatible version running on MSIE as well:

... [html]
    <script src="js/jszip.js"></script>
    <script src="js/GeoShape_compat.js"></script>
...




3. call the GeoShape.transformAndDownload(geoJSON_Object) method and provide your GeoJSON object as a parameter
