# pbi-globalization
[![Build Status](https://travis-ci.org/buttsj/pbi-globalization.svg?branch=master)](https://travis-ci.org/buttsj/pbi-globalization)
> A Power BI visualization to show data through Latitudes and Longitudes :earth_americas:  :bar_chart:

## How it works

Give the visualization a latitude + longitude coordinate, data value, and location name. The globe will display a databar at each Lat/Long location with the length determined by the value. Tooltips will hover over the **top 10** values (or top x if there is less than 10 rows).

![Image of Visualization](https://github.com/buttsj/pbi-globalization/blob/master/assets/newglobe_img.png)

![Image of Decorated Visual 1](https://github.com/buttsj/pbi-globalization/blob/master/assets/decoration1_small.png) ![Image of Decorated Visual 2](https://github.com/buttsj/pbi-globalization/blob/master/assets/decoration2_small.png) ![Image of Decorated Visual 2](https://github.com/buttsj/pbi-globalization/blob/master/assets/decoration3_small.png) ![Image of Decorated Visual 2](https://github.com/buttsj/pbi-globalization/blob/master/assets/decoration4_small.png)

## Installing this Visualization
#### Option 1 - GitHub
Navigate to the /dist/ folder and download the .pbiviz file

#### Option 2 - Microsoft AppSource Store
https://appsource.microsoft.com/en-us/product/power-bi-visuals/WA104381344

![Image of Logo](https://github.com/buttsj/pbi-globalization/blob/master/assets/appsource_page.png)


#### Installing in Power Bi Desktop/Web App

![Image of Icon](https://github.com/buttsj/pbi-globalization/blob/master/assets/globe_icon.PNG)

In the list of visuals, click the ellipsis :speech_balloon: and import the .pbiviz file into your report.

## Contributors

Jack Butts [[Github]](https://github.com/buttsj)

## Release History

* v1.0
	* Builds globe and data bars at given lat/long location
    * Slowly rotates around the globe's axis
    * Data can be filtered by outside visualizations
* v1.1
    * Globe no longer auto-rotates
    * Globe can be rotated with mouse click and drag
    * Data is now scaled down by the median of the data set (easier to see all data bars on globe) 
* v1.2
    * Data is now scaled down by the amount of the value, for better visibility
    * New required data bucket for a name of the Lat/Long location
    * Tooltips now appear on the Top 10 values (displaying Name + Value)
* v1.3
    * Background is available to be set in the properties now
    * Can toggle off Title of visual now
* v1.4
    * Set the global lighting color in properties
    * Set the global databar color in properties
* v1.5
    * Set the number of visible tool tips on screen in properties
    * Removed debugging console logs
* v1.6
    * Cleaning/refactoring code
* Possible future features:
    * Allow click filtering on data bars
    * Make each databar unique color (may be impossible)

***
###### Thanks
    * Code examples & inspiration by http://www.smartjava.org/content/render-open-data-3d-world-globe-threejs
    * Code examples & inspiration by http://stemkoski.github.io/Three.js/Labeled-Geometry.html
