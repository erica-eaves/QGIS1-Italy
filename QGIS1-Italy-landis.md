# Italy in QGIS: A Tutorial on Adding Vector Layers
### Author: Whitney.Landis@mavs.uta.edu
## This tutorial is designed so you can practice the skills you used in the [Programming Historian QGIS Tutorial about adding layers](http://programminghistorian.org/lessons/qgis-layers)

1. Make a folder or directory called **Italy** on your computer.
2. Download the following Italy data sets from DIVA-GIS into that directory and unzip them; each should be in its own sub-directory.
	* Find it by [clicking here](http://www.diva-gis.org/gdata)
	* Administrative Areas: ITA_adm
	* Roads: ITA_rds
3. Open QGIS and set up a new project.
4. Set up CRS (Coordinate Reference System) so that the project is using the Monte Mario (Rome) / Italy zone 1 (26591). You select the CRS for the project under the Project Properties.
5. Next we need to build a base map: Open these vectors, then change the way they look using the “properties”: ![new vector layer](https://cloud.githubusercontent.com/assets/22089290/18621420/9a4de1b0-7de8-11e6-99a3-36042dcff162.png)
	* ITA_adm0.shp; change so there is no color fill. (Hint:Double click the layer and change the "simple fill" style to "no brush")
	* ITA_adm1.shp; change so there is no color fill.
	* ITA_roads.shp; change the color and width of the lines so they are easier to see, if needed.
	![italy 1](https://cloud.githubusercontent.com/assets/22089290/18621383/26e29b62-7de8-11e6-93a9-a6f8d223139a.png)

6. Look at the attribute table of ITA_adm1.shp. These show the country’s regions. Note which one of the columns gives the name of the region. Note the name of that column. Close the attribute table. Go into the “properties” for ITA_adm1.shp into “labels”. Change so that your map shows the names of the regions in a large font. (Hint: Right Click the layer to find the attribute table)
	*Note: if you click the "Apply" button after font changes you can see the changes on the map without having to open and close the Properties window for more adjustments.  Also adding a buffer around the text can help with readability - I suggest white for the color and size of 0.50; but feel free to play around with the diffrent options and font sizes.)
![italy2](https://cloud.githubusercontent.com/assets/22089290/18621447/391a6a16-7de9-11e6-85c1-7b4091fd0ce4.png)
7. Open the *1870 Brue Map of Italy.* Import this file as a raster layer in QGIS. ![rasterbutton](https://cloud.githubusercontent.com/assets/22089290/18621462/6f39ddd4-7de9-11e6-9143-0cdb08bbfb30.png)
8. Go back to ITA_adm0.shp and ITA+adm1/shp and change the width of the lines so they are visible.
9. In the left-hand “layers” panel, drag the map layer so you can see the parish lines of the historical map.
![screen shot 3](https://cloud.githubusercontent.com/assets/22089290/18621478/a4ffcc08-7de9-11e6-9bce-c60a7905b47f.png)
10. Open the *Charles Scribner’s Sons 1890 Map of Italy.* Import this file as a raster layer in QGIS. Drag it in the “layers” panel just as you did the last map.
11. Go back into the Properties of your various layers. Play with border width and labels, and re-order your layers, to get a feel for the various ways you can manipulate maps in QGIS.
12. Save your work. Close QGIS.
