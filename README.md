# AgMaps Viewer
Simple web app for plotting a CSV of ag equipment onto a map. Built using [Angular 1](https://angularjs.org), [jQuery](https://jquery.com)  and [Bootstrap](http://getbootstrap.com).

## Features
* Marker clustering when zoomed out or too crowded;
* Marker coloring based on up to two columns of the CSV;
* Responsive design, primarily targeted for iPhones;
* Shortcut to navigate to marker using Apple Maps proxy for Android and iOS support.

## Technologies
|Technology                           |Version|Function                      |
|-------------------------------------|-------|------------------------------|
|[Bootstrap](http://getbootstrap.com) |3.3    |Styling and responsive design |
|[Angular.js](https://angularjs.org)  |1.4    |Multilingual support¹: English and Portuguese ([i18n](https://en.wikipedia.org/wiki/Internationalization_and_localization)) |
|[jQuery](https://jquery.com)         |1.11   |Faster Javascript development, less code |
|[Papa Parse](http://papaparse.com)   |4.1    |CSV parsing and manipulation |
|[Select2](https://select2.github.io) |3.5    |Enhanced combo/select boxes |
|[Leaflet](http://leafletjs.com)      |1.0    |Rich and interactive maps |
|[Leaflet MarkerCluster](https://github.com/Leaflet/Leaflet.markercluster) |N/A    |Marker clustering on Leaflet |

¹. English is default. Set the hash of the page to br (e.g. /index.html#br) on load to change it to Portuguese.

## Demo versions
Please refer to [this YouTube video](https://www.youtube.com/watch?v=Mq-N0kqHntk) for a live mobile demo or access the [GitHub Pages hosted version](https://pauloavelar.github.io/ag-maps) of this app.


## Disclaimer
This web app does not work when accessed with the [FILE URI scheme](https://en.wikipedia.org/wiki/File_URI_scheme) (i.e. open index.html from disk).  
Please install a web server to access the web app through [HTTP](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol).
