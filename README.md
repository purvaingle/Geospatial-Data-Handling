# Geospatial-Data-Handling

Problem Statement:
The goal of this project was to develop skills in geospatial data handling, including data collection, visualization, querying, and analysis. The following steps were taken to achieve these objectives:

## Data Collection:

Generated (longitude, latitude) pairs for 12 diverse locations on the USC campus, plus my home/apartment/dorm room.
Selected locations to cover six different schools at USC, with two locations per school.
Verified visits with selfies at each location.

## Creating a KML File:

Created a KML file using a text editor (XML format) to include placemarks for the 13 locations.
Each placemark had a label (15 characters or less) and coordinates (longitude, latitude).
Organized the 12 campus locations into KML folders.

## Visualizing Data in Google Earth:

Installed and used Google Earth to load and visualize the KML file.
Captured screenshots of the visualized data.

## Setting Up Spatial Database:

Installed Postgres with PostGIS, and consulted the spatial functions documentation.
Used online resources to run spatial queries if installation was not feasible.

## Executing Spatial Queries:

Computed the convex hull for the 13 points using spatial query functions and updated the KML file with a polygon. Verified the result in Google Earth and captured a screenshot.
Identified the four nearest neighbors of my home location, created line segments in the KML file, and verified the visualization in Google Earth with a screenshot.

## Visualizing Data with OpenLayers:

Employed OpenLayers (JavaScript API) to visualize location data.
Used HTML5 localStorage to store and retrieve the 13 sampled points, and visualized them with OpenLayers.
Developed an HTML file with JavaScript code for the visualization.

## Creating a Spirograph Curve:

Calculated spatial coordinates for a Spirograph curve centered on Tommy Trojan using parametric equations.
Generated a new KML file with Spirograph curve points, converted it to an ESRI shapefile using an online converter, and visualized the shapefile with ArcGIS Online.


## Technologies Used:
Data Collection & Verification: GPS, smartphone camera.
KML File Creation: XML text editor.
Visualization: Google Earth, ArcGIS Online.
Spatial Database: Postgres with PostGIS.
Visualization API: OpenLayers (JavaScript).
Spirograph Curve Calculation: Parametric equations, KML, ESRI shapefile converter.
