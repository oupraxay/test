# test<!DOCTYPE html>
<head>    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css"/>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_8a5bc2284f6d48c1af7b0764c8657b7e {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
            </style>
        
</head>
<body>    
    
            <div class="folium-map" id="map_8a5bc2284f6d48c1af7b0764c8657b7e" ></div>
        
</body>
<script>    
    
            var map_8a5bc2284f6d48c1af7b0764c8657b7e = L.map(
                "map_8a5bc2284f6d48c1af7b0764c8657b7e",
                {
                    center: [-27.48121, 153.00572],
                    crs: L.CRS.EPSG3857,
                    zoom: 12,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );

            

        
    
            var tile_layer_3cf93d00b15e41928d77148d538e2b21 = L.tileLayer(
                "https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",
                {"attribution": "Data by \u0026copy; \u003ca href=\"http://openstreetmap.org\"\u003eOpenStreetMap\u003c/a\u003e, under \u003ca href=\"http://www.openstreetmap.org/copyright\"\u003eODbL\u003c/a\u003e.", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            ).addTo(map_8a5bc2284f6d48c1af7b0764c8657b7e);
        
    
            var marker_0acc0bbf3add4eaf96c329e4d9d74d61 = L.marker(
                [-27.48121853, 153.005728],
                {}
            ).addTo(map_8a5bc2284f6d48c1af7b0764c8657b7e);
        
    
            var icon_f4a4485686d24fb9b32b3fcb49ebb9fd = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_0acc0bbf3add4eaf96c329e4d9d74d61.setIcon(icon_f4a4485686d24fb9b32b3fcb49ebb9fd);
        
    
        var popup_622aacff83104af590ecd6d35d33ff78 = L.popup({"maxWidth": "100%"});

        
            var html_392a142d357b4cb3999f2c6cbcd35d27 = $(`<div id="html_392a142d357b4cb3999f2c6cbcd35d27" style="width: 100.0%; height: 100.0%;">prediction 0</div>`)[0];
            popup_622aacff83104af590ecd6d35d33ff78.setContent(html_392a142d357b4cb3999f2c6cbcd35d27);
        

        marker_0acc0bbf3add4eaf96c329e4d9d74d61.bindPopup(popup_622aacff83104af590ecd6d35d33ff78)
        ;

        
    
    
            var marker_f1474db692a549fc971bf79d1314f347 = L.marker(
                [-27.46024, 153.041863],
                {}
            ).addTo(map_8a5bc2284f6d48c1af7b0764c8657b7e);
        
    
            var icon_1ac166278da343fdbaee3fde2c7c119c = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "blue", "prefix": "glyphicon"}
            );
            marker_f1474db692a549fc971bf79d1314f347.setIcon(icon_1ac166278da343fdbaee3fde2c7c119c);
        
    
        var popup_9f955ec81b3046f4b0a3a13f7cfd0ad1 = L.popup({"maxWidth": "100%"});

        
            var html_9016477ea2884cdcade2a97fe987bfd8 = $(`<div id="html_9016477ea2884cdcade2a97fe987bfd8" style="width: 100.0%; height: 100.0%;">prediction 1</div>`)[0];
            popup_9f955ec81b3046f4b0a3a13f7cfd0ad1.setContent(html_9016477ea2884cdcade2a97fe987bfd8);
        

        marker_f1474db692a549fc971bf79d1314f347.bindPopup(popup_9f955ec81b3046f4b0a3a13f7cfd0ad1)
        ;

        
    
    
            var marker_c90c5d3364fa4073869d7822fa1da8fe = L.marker(
                [-27.472559, 153.025945],
                {}
            ).addTo(map_8a5bc2284f6d48c1af7b0764c8657b7e);
        
    
            var icon_5235f19aeeb144d2a72b9d0226cd37d0 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_c90c5d3364fa4073869d7822fa1da8fe.setIcon(icon_5235f19aeeb144d2a72b9d0226cd37d0);
        
    
        var popup_1954cbb8766141e88dc4e5e0336c6d6f = L.popup({"maxWidth": "100%"});

        
            var html_077dcdbc827c4ac38ea172660553f1d3 = $(`<div id="html_077dcdbc827c4ac38ea172660553f1d3" style="width: 100.0%; height: 100.0%;">prediction 2</div>`)[0];
            popup_1954cbb8766141e88dc4e5e0336c6d6f.setContent(html_077dcdbc827c4ac38ea172660553f1d3);
        

        marker_c90c5d3364fa4073869d7822fa1da8fe.bindPopup(popup_1954cbb8766141e88dc4e5e0336c6d6f)
        ;

        
    
    
            var poly_line_95cd02fe1ab642d8bd5f58c8df4b2ca1 = L.polyline(
                [[55.6713808, 12.4533972], [55.4013094, 11.2062387], [55.3311408, 10.6322608], [55.7148992, 9.3734841], [55.8716693, 9.8839912]],
                {"bubblingMouseEvents": true, "color": "blue", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "blue", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 0.8, "smoothFactor": 1.0, "stroke": true, "weight": 2.5}
            ).addTo(map_8a5bc2284f6d48c1af7b0764c8657b7e);
        
</script>
