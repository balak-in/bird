<html>
<head>
    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://netdna.bootstrapcdn.com/bootstrap/3.0.0/css/bootstrap-glyphicons.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.2.0/css/all.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css"/>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_92356909ab35b4f2172f2c76ac817bcb {
                    position: relative;
                    width: 1750.0px;
                    height: 1000.0px;
                    left: 0.0%;
                    top: 0.0%;
                }
                .leaflet-container { font-size: 1rem; }
            </style>

            <style>html, body {
                width: 100%;
                height: 100%;
                margin: 0;
                padding: 0;
            }
            </style>

            <style>#map {
                position:absolute;
                top:0;
                bottom:0;
                right:0;
                left:0;
                }
            </style>

            <script>
                L_NO_TOUCH = false;
                L_DISABLE_3D = false;
            </script>

        
</head>
<body>
    
    
            <div class="folium-map" id="map_92356909ab35b4f2172f2c76ac817bcb" ></div>
        
</body>
<script>
    
    
            var map_92356909ab35b4f2172f2c76ac817bcb = L.map(
                "map_92356909ab35b4f2172f2c76ac817bcb",
                {
                    center: [46.82, 35.42],
                    crs: L.CRS.EPSG3857,
                    ...{
  "zoom": 12,
  "zoomControl": true,
  "preferCanvas": false,
}

                }
            );

            

        
    
            var tile_layer_4d8ae97174c0e715e8022e05a0598f72 = L.tileLayer(
                "https://tile.openstreetmap.org/{z}/{x}/{y}.png",
                {
  "minZoom": 0,
  "maxZoom": 19,
  "maxNativeZoom": 19,
  "noWrap": false,
  "attribution": "\u0026copy; \u003ca href=\"https://www.openstreetmap.org/copyright\"\u003eOpenStreetMap\u003c/a\u003e contributors",
  "subdomains": "abc",
  "detectRetina": false,
  "tms": false,
  "opacity": 1,
}

            );
        
    
            tile_layer_4d8ae97174c0e715e8022e05a0598f72.addTo(map_92356909ab35b4f2172f2c76ac817bcb);
        
    
            var feature_group_59dc00f6f2d1d197060fc56e5b03d1ec = L.featureGroup(
                {
}
            );
        
    
            var circle_marker_db6dc0f93ae507a9b9fd404c74cac0b1 = L.circleMarker(
                [46.81, 35.41],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "Red", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(feature_group_59dc00f6f2d1d197060fc56e5b03d1ec);
        
    
            feature_group_59dc00f6f2d1d197060fc56e5b03d1ec.addTo(map_92356909ab35b4f2172f2c76ac817bcb);
        
    
            var marker_450d7f8b5aaf76b590f05e36ffa030ac = L.marker(
                [46.81, 35.41],
                {
}
            ).addTo(map_92356909ab35b4f2172f2c76ac817bcb);
        
    
        var popup_e2493a9683837730b2273a6d7d08c501 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_2f479044913b2808e07143b91e92e827 = $(`<div id="html_2f479044913b2808e07143b91e92e827" style="width: 100.0%; height: 100.0%;">↙️Тип 1, СЗ, 16:30</div>`)[0];
                popup_e2493a9683837730b2273a6d7d08c501.setContent(html_2f479044913b2808e07143b91e92e827);
            
        

        marker_450d7f8b5aaf76b590f05e36ffa030ac.bindPopup(popup_e2493a9683837730b2273a6d7d08c501)
        ;

        
    
    
            var marker_7a94341fc3192ce71ad1714e0335ff0b = L.marker(
                [46.84, 35.44],
                {
}
            ).addTo(map_92356909ab35b4f2172f2c76ac817bcb);
        
    
        var popup_febc37f6eacbe09edf765e63b2994358 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_75f9cd71d7e8a7aa5011ffbb36f855dd = $(`<div id="html_75f9cd71d7e8a7aa5011ffbb36f855dd" style="width: 100.0%; height: 100.0%;">⬇️Тип 1, СЗ, 16:30</div>`)[0];
                popup_febc37f6eacbe09edf765e63b2994358.setContent(html_75f9cd71d7e8a7aa5011ffbb36f855dd);
            
        

        marker_7a94341fc3192ce71ad1714e0335ff0b.bindPopup(popup_febc37f6eacbe09edf765e63b2994358)
        ;

        
    
</script>
</html>
