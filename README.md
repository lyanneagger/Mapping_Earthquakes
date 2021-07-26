# Mapping Earthquake Data

## Overview

This map uses GeoJson data to map recent earthquakes using JavaScript, Leaflet maps, and MapBox. The default map loads with the street layer and displays all earthquake data as well as outlines for tectonic plates.

## Map Layers

The base map can be changed in the layers icon in the top right corner from the Streets layer to either the Satellite or Dark views. Changing the base map layer does not change the overlay data selected. 

The overlay data can be selected in any combination independently with options of Earthquakes, Tectonic Plates, and Major Earthquakes. The Earthquakes layer shows all recent earthquakes recorded with color coding based on magnitude. The circle marker is also scaled to reflect the magnitude. If the circle marker is clicked, the magnitude and location information will be displayed. The Tectonic Plates overlay shows a red outline of the tectonic plates. The Major Earthquakes overlay will only display markers for earthquakes with a 4.5 magnitude or greater. This overlay includes an additional color of a darker red for any magnitude greater than 6.

## Summary

The data can be looked at to compare trends in seismic activity among certain areas, where they coincide with tectonic plates meeting, and other trends.