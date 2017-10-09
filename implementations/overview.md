## Overview

This folder contains sub-folders of the various implementations of catalogs that are active in the world. Each sub-folder should
have a swagger document of its latest implementation (yaml or json are both fine), as well as one or more documents discussing
what the API handles and what choices were made in creating it.

To add an implementation create a new folder with the swagger and overview documents, and add it to the 'In Collaboration' list
below.

### In Collaboration

@TODO

### Top Potential Collaborators

@TODO

### Others

ESRI's Image Server and web service API's would be great to collaborate with. But need to figure out which part of their
extensive ecosystem makes sense. GeoNode and GeoNetwork may be interesting, though neither is focused on cataloging imagery.
But they do catalog geospatial layers, so some collaboration could be good. Descartes Labs also has a platform that searches satellite imagery, but right now it appears to just be a python API, no documented REST API. Once a core is established with one or two implementations it would be ideal to get clients testing on it - QGIS, ArcGIS, OpenLayers, GDAL, GeoTools, etc.
