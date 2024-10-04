# GeoAID: A GIS-Driven Framework for Fair Aid Distribution During Flood

## Demonstrative Working Prototype: 
https://urban-utopians.nextgis.com/resource/52/display?panel=layers

## Documentation:
Download the files and open the file with qgz extention in QGIS. You can upload the raster and vector datasets and apply various symbologies.

## Details:
Background of Our Project: During floods, when different types of aid are distributed (like relief, rescue facilities, and healthcare), we often see that the distribution isn’t done properly. Some communities receive more aid than they need, while others that urgently need help don't receive anything at all. This issue is not just local; it’s a global problem, as we found from various media reports and research papers. One of the main reasons for this inequality is that aid distributors and volunteers often lack information about which communities are more vulnerable, which ones have already received sufficient aid, and how to prioritize the distribution effectively.

To address this problem, we’re creating a GIS-based project prototype with a defined approach. For demonstration purposes, we've selected a previous flood scenario from August 28th to 30th in areas like Feni, Chittagong, Comilla, Noakhali, Lakshmipur, and surrounding regions. The reason for choosing this scenario is that during this time, floods in Feni and Chittagong were receding, but were worsening in Noakhali and Lakshmipur. However, aid continued to be directed mainly to Feni and Chittagong, leaving Noakhali and Lakshmipur underserved.

Data Collection: For vulnerability analysis, we have collected various data, including:
- Flood data: (GeoTIFF format from Sentinel-1 SAR GRD, ESA, and Google Earth Engine)
- *Road network data:*(Shape file from NASA Socio-economic Data and Application Center)
- *Digital Elevation Map:*(HGT file from NASA Shuttle Radar Topography Mission)
- Population density data: (GeoTIFF file from NASA Socio-economic Data and Application Center)
- Poverty distribution: (GeoTIFF file from NASA Socio-economic Data and Application Center)
- *Built components distribution:*(GeoTIFF file from NASA Socio-economic Data and Application Center)

We’ve initially mapped this data in QGIS for specific regions. We are working to identify correlations within this data and develop a vulnerability function. Using these insights, we are working to create strategies for aid distribution and show which communities are most affected.

The final step will be creating a priority list map by combining the vulnerability map, road access proximity, and areas that have already received sufficient aid. This map will help aid distributors and volunteers identify the communities most in need and enable them to take smarter and quicker action. We'll deploy all visualizations through a web app using the QGIS-server, making it easily accessible.

Our ultimate goal is to demonstrate that this approach can be used in any flood-affected region worldwide to ensure fair and proper aid distribution.

Our future goals on how to develop the project further:
1. Use of Real-Time Data from satellites with real-time calculations
2. To automate the whole process so that manual analysis will be no more needed.
