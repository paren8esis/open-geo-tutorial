---
title: 'Open-Geo-Tutorial: a modern open-source toolkit for geospatial and remote sensing analysis using python'
tags:
  - geospatial
  - remote sensing
  - python
  - GIS
  - machine learning
  - earth science
authors:
  - name: Patrick Gray
    orcid: 0000-0003-0872-7098
    affiliation: 1
  - name: Chris Holden
    orcid: ???
    affiliation: 2
affiliations:
 - name: Nicholas School of the Environment, Duke University
   index: 1
 - name: Department of Earth and Environment, Boston University
   index: 2
date: 6 November 2019

---

# Summary

The python ecosystem for scientific computing, visualization, geospatial analysis, and remote sensing analysis is now stable, 
powerful, and largely open-source. This allows both totally new analyses to be conducted compared to traditional GIS and 
remote sensing applications and opens these incredible tools to an entirely new community. Additionally, thanks to tools such as 
Docker and Anaconda, these tools are now both more reproducible than ever and much simpler to run on any operating system.

While much of this material can be learned via the documentation for the individual packages we introduce here, we find scientists 
early in their career, or unfamiliar with programming, are not initially comfortable with technical documentation and struggle to find 
the appropriate tools in the massive python ecosystem. `open-geo-tutorial` is a series of labs introducing students initially to 
fundamental remote sensing and GIS methodologies and gradually builds to more challenging and complex techniques such as raster 
processing, vector analysis, image classification using machine learning, time series analysis, parallalization, linkages with Google 
Earth Engine, and more all using modern open source software in Python (rasterio, shapely, GeoPandas, folium, xarray, etc).

The materials included here should take the student anywhere from 4-8 hours to work through, are designed to be worked through 
independently, and may serve as a reference for the advanced geospatial and remote sensing analyst.

# Statement of Need

Given the preponderance of academic programs in the earth and ocean sciences, geography, and even strong remote sensing programs that 
teach students graphical based geospatial and remote sensing analysis (often in expensive proprietary software applications) we found 
that students were often poorly equipped to analyze complex, highly dimensional, and large earth science datasets. Computer scientists
coming into the earth sciences on the other hand often have the programming background, but not the intuition about geospatial data. And 
neither of these groups were well versed in the modern tools that will be enable them to tackle challenging geospatial and remote sensing
analyses bringing in machine learning, parallalization, or new tools such as Google Earth Engine.

This work is aimed at both of those groups, earth scientists looking to improve their python and ability to tackle much larger problems,
and students with experience programming but little background in geospatial and remote sensing analyses. Our goal is to give a broad taste of 
the tools needed to work through challenging earth science problems, from downloading data from a NASA DAAC, to running your code in a 
reproducible Docker container, to the actually python code you'll need to run to explore the data. We think this work is especially timely
as the earth science community better understands the interconnectedness of the earth system, remote sensing tools are  larger datasets are becoming more easily avaiable the scientists tools must enable them 

# Acknowledgements

We acknowledge funding support from the North Carolina Space Grant Graduate Research Fellowship which permitted time to develop this 
open-source series and the Duke Bass Connections program for providing the space to test this series with undergraduate students.
