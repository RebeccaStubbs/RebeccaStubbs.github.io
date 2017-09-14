---
layout: post
title: Tutorials on Spatial Data in R
categories:
  - Spatial Data
  - Tutorials
date: 2017-8-14
image: https://raw.githubusercontent.com/RebeccaStubbs/rebeccastubbs.github.io/master/_posts/header_photos/hanging_clouds.JPG
image-sm: https://raw.githubusercontent.com/RebeccaStubbs/rebeccastubbs.github.io/master/_posts/header_photos/hanging_clouds.JPG
---

Spatial data can be tricky. To help new users find their footing in spatial data analysis, I've written a handful of documents to help orient R users to the nuances of spatial data. For now, these tutorials reside on RPubs, a freely hosted site for R users to publish markdown documents. 

See the listings below, or feel free to check out my [RPubs](https://rpubs.com/BeccaStubbs/) for a full listing of the tutorial materials I have there.

## [Bringing Shapefiles into R](https://rpubs.com/BeccaStubbs/bringing_shapefiles_into_R)

This tutorial breaks down the "shapefile" as a file format, and shows how to load polgyon shapefiles into R. 

## [Polygons to Pixels](https://rpubs.com/BeccaStubbs/polygons_to_pixels)

So, you have polygon data--- but what if you want to represent that in a raster/pixel format? This goes through the nuts and bolts of how to think about polygon resampling, and one approach to do so.

## [The Scrambled Polygon Problem](https://rpubs.com/BeccaStubbs/scrambled_polygons)

An obnoxious quirk of the R SpatialPolygonsDataFrame objects is that the geometry is only affiliated with the attributes based on the ordering of the two "halves" of the spatial data lining up. If you undertake a base::merge() operation, sometimes, this order can be tampered with! This tutorial explains this problem in-depth and poses a few solutions and safeguards. 

