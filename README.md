# Satellite_Imagery
This repository contains python codes for analysing geo-spatial data. The dataset is satellite data from Landsat8 downloaded using USGS Earth Explorer.

*Satellite_Data_Classification.ipynb* - The notebook calculates NVDI and classifies land and sea. For the classification, k-means clustering is used with the cluster size 8. Using data from all the seven bands provides more accurate classification than using data from a single band.
