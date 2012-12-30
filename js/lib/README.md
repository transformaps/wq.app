# Third party libraries

These are the dependencies of various wq.app modules as well as some other useful libraries.  Most of these have been patched to support better integration as AMD modules.

## Library versions

Library                                                  |  Version  |  Notes
-------------------------------------------------------- | --------- | -------------------------------------------
[d3.js](/mbostock/d3)                                    |   2.10.3  |  wrapped as AMD module
[es5-shim.js](/kriskowal/es5-shim)                       |    2.0.5  |  no changes
[jquery](/jquery/jquery)                                 |    1.8.2  |  patched to define anonymous AMD module
[jquery.mobile](/jquery/jquery-mobile)                   |    1.2.0  |  patched to ensure router loads first<br>make resetActivePageHeight configurable
[jquery.mobile.router](/azicchetti/jquerymobile-router)  |     0.93  |  patched with relative jQuery dependency
[jquery.validate](/jzaefferer/jquery-validation)         |   1.10.0  |  wrapped as AMD module
[leaflet](/CloudMade/Leaflet)                            |    0.4.4  |  wrapped as AMD module<br>patched _layersMinZoom computation in Map.addLayer<br>commented out disableClickPropagation in Popup._initLayout
[leaflet.markercluster](/danzel/Leaflet.markercluster)   |  315c2c8  |  wrapped as AMD module
[mustache.js](/janl/mustache.js)                         |    0.7.0  |  no changes
[proj4js](http://trac.osgeo.org/proj4js/)                |    1.1.0  |  wrapped as AMD module
[proj4leaflet](/kartena/Proj4Leaflet)                    |  219fc47  |  wrapped as AMD module
[requirejs](/jrburke/requirejs)                          |    2.0.6  |  no changes
[rtree.js](/imbcmdth/RTree)                              |    0.6.2  |  wrapped as AMD module 