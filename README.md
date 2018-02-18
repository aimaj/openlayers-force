# openlayers-force
- Basic OpenLayers infrastructure
   - iFrame OpenLayers map
   - Spawns a marker at a default or predefined location
   - Responds to click events on the marker
   - The marker has an infowindow showing off data from the ‘object’ the marker represents
   - TBD: Inbuilt geocoding, marker can be considered to be lat/lon + street address
- Lightning component containing the map
   - Can pass a list of records to render as markers
   - Can request the main markers location from the iframe
