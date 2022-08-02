<!doctype html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="initial-scale=1,user-scalable=no,maximum-scale=1,width=device-width">
        <meta name="mobile-web-app-capable" content="yes">
        <meta name="apple-mobile-web-app-capable" content="yes">
        <link rel="stylesheet" href="css/leaflet.css">
        <link rel="stylesheet" href="css/qgis2web.css"><link rel="stylesheet" href="css/fontawesome-all.min.css">
        <link rel="stylesheet" href="css/leaflet-search.css">
        <link rel="stylesheet" href="css/leaflet-control-geocoder.Geocoder.css">
        <style>
        html, body, #map {
            width: 100%;
            height: 100%;
            padding: 0;
            margin: 0;
        }
        </style>
        <title></title>
    </head>
    <body>
        <div id="map">
        </div>
        <script src="js/qgis2web_expressions.js"></script>
        <script src="js/leaflet.js"></script>
        <script src="js/leaflet-svg-shape-markers.min.js"></script>
        <script src="js/leaflet.rotatedMarker.js"></script>
        <script src="js/leaflet.pattern.js"></script>
        <script src="js/leaflet-hash.js"></script>
        <script src="js/Autolinker.min.js"></script>
        <script src="js/rbush.min.js"></script>
        <script src="js/labelgun.min.js"></script>
        <script src="js/labels.js"></script>
        <script src="js/leaflet-control-geocoder.Geocoder.js"></script>
        <script src="js/leaflet-search.js"></script>
        <script src="data/STPs_region_0.js"></script>
        <script src="data/202208CDCs_1.js"></script>
        <script src="data/202207Hubscsvexport_2.js"></script>
        <script src="data/202207Tier1hospitalscsvexport_3.js"></script>
        <script>
        var highlightLayer;
        function highlightFeature(e) {
            highlightLayer = e.target;

            if (e.target.feature.geometry.type === 'LineString') {
              highlightLayer.setStyle({
                color: '#ffff00',
              });
            } else {
              highlightLayer.setStyle({
                fillColor: '#ffff00',
                fillOpacity: 1
              });
            }
            highlightLayer.openPopup();
        }
        var map = L.map('map', {
            zoomControl:true, maxZoom:28, minZoom:1
        }).fitBounds([[50.37602469217336,-6.0148330074764065],[54.08626458829894,2.273892472495779]]);
        var hash = new L.Hash(map);
        map.attributionControl.setPrefix('<a href="https://github.com/tomchadwin/qgis2web" target="_blank">qgis2web</a> &middot; <a href="https://leafletjs.com" title="A JS library for interactive maps">Leaflet</a> &middot; <a href="https://qgis.org">QGIS</a>');
        var autolinker = new Autolinker({truncate: {length: 30, location: 'smart'}});
        var bounds_group = new L.featureGroup([]);
        function setBounds() {
        }
        function pop_STPs_region_0(feature, layer) {
            layer.on({
                mouseout: function(e) {
                    for (i in e.target._eventParents) {
                        e.target._eventParents[i].resetStyle(e.target);
                    }
                    if (typeof layer.closePopup == 'function') {
                        layer.closePopup();
                    } else {
                        layer.eachLayer(function(feature){
                            feature.closePopup()
                        });
                    }
                },
                mouseover: highlightFeature,
            });
            var popupContent = '<table>\
                    <tr>\
                        <td colspan="2">' + (feature.properties['objectid'] !== null ? autolinker.link(feature.properties['objectid'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <td colspan="2">' + (feature.properties['stp20cd'] !== null ? autolinker.link(feature.properties['stp20cd'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <td colspan="2"><strong>stp20nm</strong><br />' + (feature.properties['stp20nm'] !== null ? autolinker.link(feature.properties['stp20nm'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <td colspan="2">' + (feature.properties['bng_e'] !== null ? autolinker.link(feature.properties['bng_e'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <td colspan="2">' + (feature.properties['bng_n'] !== null ? autolinker.link(feature.properties['bng_n'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <td colspan="2">' + (feature.properties['long'] !== null ? autolinker.link(feature.properties['long'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <td colspan="2">' + (feature.properties['lat'] !== null ? autolinker.link(feature.properties['lat'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <td colspan="2">' + (feature.properties['st_areashape'] !== null ? autolinker.link(feature.properties['st_areashape'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <td colspan="2">' + (feature.properties['st_lengthshape'] !== null ? autolinker.link(feature.properties['st_lengthshape'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <td colspan="2">' + (feature.properties['Sustainability_Transformation_Partnerships_and_NHS_England__Region___April_2020__Lookup_in_England_FID'] !== null ? autolinker.link(feature.properties['Sustainability_Transformation_Partnerships_and_NHS_England__Region___April_2020__Lookup_in_England_FID'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <td colspan="2">' + (feature.properties['Sustainability_Transformation_Partnerships_and_NHS_England__Region___April_2020__Lookup_in_England_STP20CDH'] !== null ? autolinker.link(feature.properties['Sustainability_Transformation_Partnerships_and_NHS_England__Region___April_2020__Lookup_in_England_STP20CDH'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <td colspan="2">' + (feature.properties['Sustainability_Transformation_Partnerships_and_NHS_England__Region___April_2020__Lookup_in_England_STP20NM'] !== null ? autolinker.link(feature.properties['Sustainability_Transformation_Partnerships_and_NHS_England__Region___April_2020__Lookup_in_England_STP20NM'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <td colspan="2">' + (feature.properties['Sustainability_Transformation_Partnerships_and_NHS_England__Region___April_2020__Lookup_in_England_NHSER20CD'] !== null ? autolinker.link(feature.properties['Sustainability_Transformation_Partnerships_and_NHS_England__Region___April_2020__Lookup_in_England_NHSER20CD'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <td colspan="2">' + (feature.properties['Sustainability_Transformation_Partnerships_and_NHS_England__Region___April_2020__Lookup_in_England_NHSER20CDH'] !== null ? autolinker.link(feature.properties['Sustainability_Transformation_Partnerships_and_NHS_England__Region___April_2020__Lookup_in_England_NHSER20CDH'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <td colspan="2">' + (feature.properties['Sustainability_Transformation_Partnerships_and_NHS_England__Region___April_2020__Lookup_in_England_NHSER20NM'] !== null ? autolinker.link(feature.properties['Sustainability_Transformation_Partnerships_and_NHS_England__Region___April_2020__Lookup_in_England_NHSER20NM'].toLocaleString()) : '') + '</td>\
                    </tr>\
                </table>';
            layer.bindPopup(popupContent, {maxHeight: 400});
        }

        function style_STPs_region_0_0(feature) {
            switch(String(feature.properties['Sustainability_Transformation_Partnerships_and_NHS_England__Region___April_2020__Lookup_in_England_NHSER20NM'])) {
                case 'East of England':
                    return {
                pane: 'pane_STPs_region_0',
                opacity: 1,
                color: 'rgba(112,112,112,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1.0, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(222,192,219,1.0)',
                interactive: false,
            }
                    break;
                case 'London':
                    return {
                pane: 'pane_STPs_region_0',
                opacity: 1,
                color: 'rgba(112,112,112,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1.0, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(219,207,138,1.0)',
                interactive: false,
            }
                    break;
                case 'Midlands':
                    return {
                pane: 'pane_STPs_region_0',
                opacity: 1,
                color: 'rgba(112,112,112,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1.0, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(218,239,236,1.0)',
                interactive: false,
            }
                    break;
                case 'North East and Yorkshire':
                    return {
                pane: 'pane_STPs_region_0',
                opacity: 1,
                color: 'rgba(112,112,112,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1.0, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(222,234,198,1.0)',
                interactive: false,
            }
                    break;
                case 'North West':
                    return {
                pane: 'pane_STPs_region_0',
                opacity: 1,
                color: 'rgba(112,112,112,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1.0, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(206,238,209,1.0)',
                interactive: false,
            }
                    break;
                case 'South East':
                    return {
                pane: 'pane_STPs_region_0',
                opacity: 1,
                color: 'rgba(112,112,112,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1.0, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(204,216,234,1.0)',
                interactive: false,
            }
                    break;
                case 'South West':
                    return {
                pane: 'pane_STPs_region_0',
                opacity: 1,
                color: 'rgba(112,112,112,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1.0, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(216,204,239,1.0)',
                interactive: false,
            }
                    break;
                default:
                    return {
                pane: 'pane_STPs_region_0',
                opacity: 1,
                color: 'rgba(35,35,35,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1.0, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(209,98,117,1.0)',
                interactive: false,
            }
                    break;
            }
        }
        map.createPane('pane_STPs_region_0');
        map.getPane('pane_STPs_region_0').style.zIndex = 400;
        map.getPane('pane_STPs_region_0').style['mix-blend-mode'] = 'normal';
        var layer_STPs_region_0 = new L.geoJson(json_STPs_region_0, {
            attribution: '',
            interactive: false,
            dataVar: 'json_STPs_region_0',
            layerName: 'layer_STPs_region_0',
            pane: 'pane_STPs_region_0',
            onEachFeature: pop_STPs_region_0,
            style: style_STPs_region_0_0,
        });
        bounds_group.addLayer(layer_STPs_region_0);
        map.addLayer(layer_STPs_region_0);
        function pop_202208CDCs_1(feature, layer) {
            layer.on({
                mouseout: function(e) {
                    for (i in e.target._eventParents) {
                        e.target._eventParents[i].resetStyle(e.target);
                    }
                    if (typeof layer.closePopup == 'function') {
                        layer.closePopup();
                    } else {
                        layer.eachLayer(function(feature){
                            feature.closePopup()
                        });
                    }
                },
                mouseover: highlightFeature,
            });
            var popupContent = '<table>\
                    <tr>\
                        <th scope="row">STP</th>\
                        <td>' + (feature.properties['STP'] !== null ? autolinker.link(feature.properties['STP'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">CDC name</th>\
                        <td>' + (feature.properties['CDC name'] !== null ? autolinker.link(feature.properties['CDC name'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">Type</th>\
                        <td>' + (feature.properties['Type'] !== null ? autolinker.link(feature.properties['Type'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">Sub-Type</th>\
                        <td>' + (feature.properties['Sub-Type'] !== null ? autolinker.link(feature.properties['Sub-Type'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">Postcode</th>\
                        <td>' + (feature.properties['Postcode'] !== null ? autolinker.link(feature.properties['Postcode'].toLocaleString()) : '') + '</td>\
                    </tr>\
                </table>';
            layer.bindPopup(popupContent, {maxHeight: 400});
        }

        function style_202208CDCs_1_0() {
            return {
                pane: 'pane_202208CDCs_1',
                shape: 'diamond',
                radius: 8.8,
                opacity: 1,
                color: 'rgba(128,17,25,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 2.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(219,30,42,1.0)',
                interactive: true,
            }
        }
        map.createPane('pane_202208CDCs_1');
        map.getPane('pane_202208CDCs_1').style.zIndex = 401;
        map.getPane('pane_202208CDCs_1').style['mix-blend-mode'] = 'normal';
        var layer_202208CDCs_1 = new L.geoJson(json_202208CDCs_1, {
            attribution: '',
            interactive: true,
            dataVar: 'json_202208CDCs_1',
            layerName: 'layer_202208CDCs_1',
            pane: 'pane_202208CDCs_1',
            onEachFeature: pop_202208CDCs_1,
            pointToLayer: function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.shapeMarker(latlng, style_202208CDCs_1_0(feature));
            },
        });
        bounds_group.addLayer(layer_202208CDCs_1);
        map.addLayer(layer_202208CDCs_1);
        function pop_202207Hubscsvexport_2(feature, layer) {
            layer.on({
                mouseout: function(e) {
                    for (i in e.target._eventParents) {
                        e.target._eventParents[i].resetStyle(e.target);
                    }
                    if (typeof layer.closePopup == 'function') {
                        layer.closePopup();
                    } else {
                        layer.eachLayer(function(feature){
                            feature.closePopup()
                        });
                    }
                },
                mouseover: highlightFeature,
            });
            var popupContent = '<table>\
                    <tr>\
                        <th scope="row">Region</th>\
                        <td>' + (feature.properties['Region'] !== null ? autolinker.link(feature.properties['Region'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">STP</th>\
                        <td>' + (feature.properties['STP'] !== null ? autolinker.link(feature.properties['STP'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">Hub name</th>\
                        <td>' + (feature.properties['CDC name'] !== null ? autolinker.link(feature.properties['CDC name'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">Type</th>\
                        <td>' + (feature.properties['Type'] !== null ? autolinker.link(feature.properties['Type'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">Sub-Type</th>\
                        <td>' + (feature.properties['Sub-Type'] !== null ? autolinker.link(feature.properties['Sub-Type'].toLocaleString()) : '') + '</td>\
                    </tr>\
                </table>';
            layer.bindPopup(popupContent, {maxHeight: 400});
        }

        function style_202207Hubscsvexport_2_0(feature) {
            switch(String(feature.properties['Sub-Type'])) {
                case 'Existing':
                    return {
                pane: 'pane_202207Hubscsvexport_2',
                radius: 10.0,
                opacity: 1,
                color: 'rgba(255,255,255,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 4.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(0,94,184,1.0)',
                interactive: true,
            }
                    break;
                case 'New Hub':
                    return {
                pane: 'pane_202207Hubscsvexport_2',
                radius: 10.0,
                opacity: 1,
                color: 'rgba(255,255,255,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 4.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(166,206,227,1.0)',
                interactive: true,
            }
                    break;
                default:
                    return {
                pane: 'pane_202207Hubscsvexport_2',
                radius: 10.0,
                opacity: 1,
                color: 'rgba(255,255,255,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 2.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(206,90,28,1.0)',
                interactive: true,
            }
                    break;
            }
        }
        map.createPane('pane_202207Hubscsvexport_2');
        map.getPane('pane_202207Hubscsvexport_2').style.zIndex = 402;
        map.getPane('pane_202207Hubscsvexport_2').style['mix-blend-mode'] = 'normal';
        var layer_202207Hubscsvexport_2 = new L.geoJson(json_202207Hubscsvexport_2, {
            attribution: '',
            interactive: true,
            dataVar: 'json_202207Hubscsvexport_2',
            layerName: 'layer_202207Hubscsvexport_2',
            pane: 'pane_202207Hubscsvexport_2',
            onEachFeature: pop_202207Hubscsvexport_2,
            pointToLayer: function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.circleMarker(latlng, style_202207Hubscsvexport_2_0(feature));
            },
        });
        bounds_group.addLayer(layer_202207Hubscsvexport_2);
        map.addLayer(layer_202207Hubscsvexport_2);
        function pop_202207Tier1hospitalscsvexport_3(feature, layer) {
            layer.on({
                mouseout: function(e) {
                    for (i in e.target._eventParents) {
                        e.target._eventParents[i].resetStyle(e.target);
                    }
                    if (typeof layer.closePopup == 'function') {
                        layer.closePopup();
                    } else {
                        layer.eachLayer(function(feature){
                            feature.closePopup()
                        });
                    }
                },
                mouseover: highlightFeature,
            });
            var popupContent = '<table>\
                    <tr>\
                        <th scope="row">Regions</th>\
                        <td>' + (feature.properties['Regions'] !== null ? autolinker.link(feature.properties['Regions'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <td colspan="2"><strong>Provider</strong><br />' + (feature.properties['Provider'] !== null ? autolinker.link(feature.properties['Provider'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">Postcode</th>\
                        <td>' + (feature.properties['Postcode'] !== null ? autolinker.link(feature.properties['Postcode'].toLocaleString()) : '') + '</td>\
                    </tr>\
                </table>';
            layer.bindPopup(popupContent, {maxHeight: 400});
        }

        function style_202207Tier1hospitalscsvexport_3_0() {
            return {
                pane: 'pane_202207Tier1hospitalscsvexport_3',
                shape: 'triangle',
                radius: 8.0,
                opacity: 1,
                color: 'rgba(255,255,255,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 2.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(0,0,0,1.0)',
                interactive: true,
            }
        }
        map.createPane('pane_202207Tier1hospitalscsvexport_3');
        map.getPane('pane_202207Tier1hospitalscsvexport_3').style.zIndex = 403;
        map.getPane('pane_202207Tier1hospitalscsvexport_3').style['mix-blend-mode'] = 'normal';
        var layer_202207Tier1hospitalscsvexport_3 = new L.geoJson(json_202207Tier1hospitalscsvexport_3, {
            attribution: '',
            interactive: true,
            dataVar: 'json_202207Tier1hospitalscsvexport_3',
            layerName: 'layer_202207Tier1hospitalscsvexport_3',
            pane: 'pane_202207Tier1hospitalscsvexport_3',
            onEachFeature: pop_202207Tier1hospitalscsvexport_3,
            pointToLayer: function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.shapeMarker(latlng, style_202207Tier1hospitalscsvexport_3_0(feature));
            },
        });
        bounds_group.addLayer(layer_202207Tier1hospitalscsvexport_3);
        map.addLayer(layer_202207Tier1hospitalscsvexport_3);
        var osmGeocoder = new L.Control.Geocoder({
            collapsed: true,
            position: 'topleft',
            text: 'Search',
            title: 'Testing'
        }).addTo(map);
        document.getElementsByClassName('leaflet-control-geocoder-icon')[0]
        .className += ' fa fa-search';
        document.getElementsByClassName('leaflet-control-geocoder-icon')[0]
        .title += 'Search for a place';
        var baseMaps = {};
        L.control.layers(baseMaps,{'<img src="legend/202207Tier1hospitalscsvexport_3.png" /> 2022-07-Tier-1-hospitals-csvexport': layer_202207Tier1hospitalscsvexport_3,'2022-07-Hubs-csvexport<br /><table><tr><td style="text-align: center;"><img src="legend/202207Hubscsvexport_2_Existing0.png" /></td><td>Existing</td></tr><tr><td style="text-align: center;"><img src="legend/202207Hubscsvexport_2_NewHub1.png" /></td><td>New Hub</td></tr><tr><td style="text-align: center;"><img src="legend/202207Hubscsvexport_2_2.png" /></td><td></td></tr></table>': layer_202207Hubscsvexport_2,'<img src="legend/202208CDCs_1.png" /> 2022-08-CDCs': layer_202208CDCs_1,'STPs_region<br /><table><tr><td style="text-align: center;"><img src="legend/STPs_region_0_EastofEngland0.png" /></td><td>East of England</td></tr><tr><td style="text-align: center;"><img src="legend/STPs_region_0_London1.png" /></td><td>London</td></tr><tr><td style="text-align: center;"><img src="legend/STPs_region_0_Midlands2.png" /></td><td>Midlands</td></tr><tr><td style="text-align: center;"><img src="legend/STPs_region_0_NorthEastandYorkshire3.png" /></td><td>North East and Yorkshire</td></tr><tr><td style="text-align: center;"><img src="legend/STPs_region_0_NorthWest4.png" /></td><td>North West</td></tr><tr><td style="text-align: center;"><img src="legend/STPs_region_0_SouthEast5.png" /></td><td>South East</td></tr><tr><td style="text-align: center;"><img src="legend/STPs_region_0_SouthWest6.png" /></td><td>South West</td></tr><tr><td style="text-align: center;"><img src="legend/STPs_region_0_7.png" /></td><td></td></tr></table>': layer_STPs_region_0,}).addTo(map);
        setBounds();
        map.addControl(new L.Control.Search({
            layer: layer_202207Tier1hospitalscsvexport_3,
            initial: false,
            hideMarkerOnCollapse: true,
            propertyName: 'Provider'}));
        document.getElementsByClassName('search-button')[0].className +=
         ' fa fa-binoculars';
        resetLabels([layer_202207Hubscsvexport_2,layer_202207Tier1hospitalscsvexport_3]);
        map.on("zoomend", function(){
            resetLabels([layer_202207Hubscsvexport_2,layer_202207Tier1hospitalscsvexport_3]);
        });
        map.on("layeradd", function(){
            resetLabels([layer_202207Hubscsvexport_2,layer_202207Tier1hospitalscsvexport_3]);
        });
        map.on("layerremove", function(){
            resetLabels([layer_202207Hubscsvexport_2,layer_202207Tier1hospitalscsvexport_3]);
        });
        </script>
    </body>
</html>
