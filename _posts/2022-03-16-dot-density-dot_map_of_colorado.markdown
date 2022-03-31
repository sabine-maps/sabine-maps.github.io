---
layout: post
title:  "Dot Density Map of Colorado"
date:  2022-03-16   
categories: QGIS
tags:
  - QGIS
  - dot density
  - Colorado
permalink: /:title
---

Dot density maps can be [beautiful](http://uxblog.idvsolutions.com/2013/01/people-dots-seattle-area-commuting.html), [informative](https://www.cnn.com/interactive/2021/us/census-race-ethnicity-map/) , and really [intuitive](https://www.esri.com/arcgis-blog/products/arcgis-living-atlas/analytics/multivariate-dot-density/?rmedium=redirect&rsource=blogs.esri.com/esri/arcgis/2018/01/29/multivariate-dot-density) ways of visualizing populations and groupings within them.  For my first foray into QGIS, I wanted to create a simple one-person-one-dot map .  I chose Colorado, a state that is divided roughly down the middle by the Rocky Mountains and where the majority of the population is concentrated along the Front Range.

I used [data from the 2020 census from the Colorado State Demography office](https://demography.dola.colorado.gov/assets/html/gis.html).  There are 140,345 census blocks in Colorado, and the total population according to the decennial census is 5,773,714.

I followed [this lovely tutorial](https://www.maartenlambrechts.com/2018/02/13/one-person-one-dot-maps-and-how-to-make-them.html) from Maarten Lambrechts to create my map.  

