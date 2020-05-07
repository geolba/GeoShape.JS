# GeoShape.JS
Javascript converter from geoJSON to ESRI shapefile (Miroslav Janata, mirajanata@volny.cz)


# Usage
1. Download the project files

2. Reference the source javascript files in your web page:

...
    <script src="js/jszip.js"></script>

    <script src="js/GeoShape.js"></script>
...

Alternatively you can use more browser compatible version running on MSIE as well:

...
    <script src="js/jszip.js"></script>

    <script src="js/GeoShape_compat.js"></script>
...




3. call the GeoShape.transformAndDownload(geoJSON_Object) method