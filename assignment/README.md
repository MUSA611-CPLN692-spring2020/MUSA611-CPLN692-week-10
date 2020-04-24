# Final Project Proposal

*****
Yuyang Yin & Junya Chen

## Problem / Question


******
We want to build a dashboard that could present our Advanced GIS term project. The term project is about real estate development suitability assessment. There are 3 main parts of the project, which are development activeness map, development suitability map, and infrastructure development locator. Most of the maps are maps with hexagons. We want to create a dashboard that could show different sections of our map (different pages for each section), and display different layers according to its attribute table. Ideally, we want to show the dashboard in 3D format, which can be more visually attractive. Tools like draw polygons can be used to calculate the mean index value within the polygon.

## The data

******
The dataset we want to use is processed and analyzed by ourselves in ArcGIS based on related shapefiles from San Francisco open data. The dataset is a hexagon shapefile with various attributes, which can be ideally converted to geojson format using converters available online.
The datasets covers:
        Transportation service area
        Infrastructure
        Housing
        Population
        Income
        Landuse
        Elevation
        Floodplain
        Etc.


## Technologies used

******
Leaflet
    Present and create interactive maps
Turf
    Draw polygons
Underscore
    Filter
jQuery



## Design spec

#### User experience
******
 The users of our applications are real estate developers and city governors who are seeking sites to do real estate or infrastructure development. They can use our map to quickly identify sites that have great development potential. This dashboard could be a helpful tool in the decision-making process.


#### Layouts and visual design
*******

A floating sidebar that could potentially hide when a button was clicked
A clear legend that could update with the map
An interactive table or chart could be shown when the slide bar was used.

## Anticipated difficulties
******

The difficult part is to convey the information clearly in the dashboard, how can we reflect a larger scale performance instead of a single hexagon. 3D format might also be a challenging part of this project.

## Missing pieces
******
Charts could reflect only the data / values of the polygons selected
3D visualization
