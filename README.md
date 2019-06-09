
    var elgnowo_test_tiles = L.tileLayer('file:///C:/Users/luki/Desktop/New folder/aaaaaaaaaaa/{z}/{x}/{y}.png', {
	    attribution: 'Rights: Lukasz Gorny',
        maxNativeZoom: 22,
        maxZoom:22
    });

Where:
    
minZoom Number:  Minimum zoom number.<br />
maxZoom Number:  Maximum zoom number.<br />
maxNativeZoom:   Maximum zoom number the tiles source has available. If it is specified, the tiles on all zoom levels higher than maxNativeZoom will be loaded from maxZoom level and auto-scaled. 

Leaflet.js map with tiles generated from the vector layer.<br />
URL:  https://gornymooj.github.io/oversized_tiles_scale_leaflet/index.html 

Leaflet.js map with tiles generated from the image layer.<br />
URL:  https://gornymooj.github.io/oversized_tiles_scale_leaflet/index_2.html 
<br />
