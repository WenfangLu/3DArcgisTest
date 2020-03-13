# 3DArcgisTest
A simple 3D datavisualization demo to test Arcgis 4.14 JavaScript API 

## Using SceneView With featureLayer to show data in 2D and 3D 

### How to make it 

First, a FeatureLayer is a single layer that can be created from a Map Service or Feature Service, thus 

### Import Arcgis api 

`<link rel="stylesheet" href="https://js.arcgis.com/4.14/esri/themes/light/main.css">`

`  <script src="https://js.arcgis.com/4.14/"></script>`

Then we use require to import three things to help us to make data visulization

`require([
            "esri/Map",
            "esri/views/SceneView",
            "esri/layers/FeatureLayer"
        ],function(
            Map,SceneView,FeatureLayer
        ){  /* code goes here */ 
 }`

For more details, you can see the codes to know how to implement 3D data visualization

#### Layer service provided by ArcGIS 

1. the well map service  : the service provides us to show depth in 3D by the attribute of height 
2. the quake map service : the service provides us to show the magnitudes of the earthquakes in two dimensions an the depths in three dimensions.    


#### Renderer

Features in a FeatureLayer are visualized by setting a Renderer to the renderer property of the layer

Reference: https://developers.arcgis.com/javascript/latest/api-reference/esri-renderers-Renderer.html

#### FeatureLayer

Reference: https://developers.arcgis.com/javascript/latest/api-reference/esri-layers-FeatureLayer.html

#### PopUpTemplate

Reference:https://developers.arcgis.com/javascript/latest/api-reference/esri-PopupTemplate.html
