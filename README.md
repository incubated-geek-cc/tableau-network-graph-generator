# Tableau Data Utility
## Objective: Making Tableau users' lives easier in data preparation for data visualisation
### View [app demo](https://tableau-data-utility.herokuapp.com/) deployed on Heroku 

### General Functionalities
* Input user's data file(s)
* Export of generated transformed data files 

### 1. Generate Network Graph Data for Tableau
Adjustment specific positiosn of nodes to alter network graph layout
<br/>**Demo:**<br/>![Demo of Layout Adjustment](https://miro.medium.com/max/960/1*_XoEvi8yXSj8uXXuGkuVdA.gif)
<br/>**Before Adjustment:**<br/>![Before Adjustment](https://miro.medium.com/max/1050/1*4YFXQc3_ZoccWZ26FPkNyg.png)<br/>
<br/>**After Adjustment:**<br/>![After Adjustment](https://miro.medium.com/max/1050/1*x3sAFb5uR13G3H-mC3Ye3A.png)
---
Adjustment of d3 network graph layout parameters: `size` `distance` `strength` `collide`
<br/>![Parameter Adjustments](https://miro.medium.com/max/1050/1*m7G3SaYIAJg1kEd7UQiv0g.png)
<br/>More information found at https://towardsdatascience.com/leverage-on-d3-js-v4-to-build-a-network-graph-for-tableau-with-ease-cc274cba69ce

### 2. Generate Spatial Data for Tableau
Map Polygons in Tableau with CSV Output File:
<br/>![Mapping Polygons](https://miro.medium.com/max/1050/1*E89DZBCpjkeFZRjDMbnx6Q.png)
---
Transform GeoJSON to CSV to visualise mixed-geometry types in Tableau in a single setting:
<br/>![Mixed Geometry in Tableau](https://miro.medium.com/max/1050/1*GmNm1806e1Gzf-3mgWlfcA.png)
---
Export required basemap with coordinates auto-generated:
<br/>![Export Basemap](https://miro.medium.com/max/1050/1*MphBS1k898lJVQz5dXFUDg.png)
---
Input basemap image and coordinates:
<br/>![Input Basemap](https://miro.medium.com/max/1050/1*rNnGPA07Mtw3J5sJ0yI3Mw.png)
---
Basemap has been imported into Tableau:
<br/>![Basemap imported](https://miro.medium.com/max/1050/1*UalgzAr7SvSTfhFKEwA2nw.png)
---
Convert spatial files SHP & KML to GeoJSON format:
<br/>![Spatial Conversion](https://miro.medium.com/max/1050/1*HQxDm2dxxPPsuKQC5DStpg.png)
<br/>More information found at https://towardsdatascience.com/underrated-combined-functionalities-of-tableau-point-linestring-polygon-mapping-b4c0568a4de2

### 3. Generate Hex Maps Data for Tableau
Toggle Parameters for Hex Map generated by final GeoJSON output:
<br/>![Toggle Hex Parameters](https://miro.medium.com/max/1050/1*5DOVcf78VDX77JMHs5f60g.png)
---
Output GeoJSON file rendering Hex Maps:
<br/>![Hex Map rendered](https://miro.medium.com/max/1050/1*5E_S69SNwk5sZxrMj6Iiog.png)
---
Convert spatial files SHP & KML to GeoJSON format:
<br/>![Spatial Conversion](https://miro.medium.com/max/1050/1*HQxDm2dxxPPsuKQC5DStpg.png)
<br/>More information found at https://geek-cc.medium.com/generate-hex-maps-from-your-existing-spatial-data-in-less-than-3-steps-a6f39d778d84