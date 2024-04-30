# SP2024-FP05-gravity

## Comparing Gravity Changes Before and After Earthquakes
### Bianca Riebe @biancaann6 and Kaitlyn Manalili @kmanalili

### Problem Objective

The purpose of this project is to compare observed gravity changes before and after earthquakes. 

### Introduction

Multiple datasets with earthquake and gravity data were analyzed to show how gravity changes before/after different earthquakes. The earthquakes analyzed are the Tohoku-Oki Earthquake off the coast of Japan (magnitude 9.0) and the Lushan Earthquake in China (magnitude 7.0). 

### How to use this repository

- Data sources are availible in the README file to download
- Code for figure development with this data is availible in the notebooks folder
- Resulting figures are in the figures folder
- Dev folder contains initial exploration of the data
- Environment is held in environment.yml
- Overall presentation is in notebooks/FP05-Presentation

### Datasets

[Lushan Data](https://zenodo.org/records/7855090)

[Tohoku-Oki Data](https://www.eas.slu.edu/GGP/tohoku2011/second/)

[Topography Data](https://www.ngdc.noaa.gov/thredds/catalog/global/ETOPO2022/60s/60s_bed_elev_netcdf/catalog.html?dataset=globalDatasetScan/ETOPO2022/60s/60s_bed_elev_netcdf/ETOPO_2022_v1_60s_N90W180_bed.nc)


### Tools/packages

- [Pandas](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.html) Pandas was used to open our data and clean our data.
- [Numpy](https://numpy.org/) Numpy was used to to further analyze and manipulate data. 
- [Matplotlib](https://matplotlib.org/) Matplotlib was used to make visualizations of our data. This will especially allow us to compare data when we are presenting the outcomes of the project. 
- [Xarray](https://docs.xarray.dev/en/stable/) Xarray was used to parse our data and understand the data.
- [Cartopy](https://scitools.org.uk/cartopy/docs/latest/) Cartopy was used to form our map figures.

### Plans Methodology/approach

To approach our project, we found two data sets with gravitational data recorded throughout a range before and after the eathquakes occurance. We plan to use Xarray and Pandas to analyze our data for gravitational trends and eventually use matplotlib to produce effective and clear visualizations of how gravity can change before an earthquake. 

### Expected Outcomes

The Tohoku-Oki earthquake had the largest change in observed gravity before the earthquake, out of the two earthquakes whose data our group will analyze. Both datasets should show that there is a change in observed gravity before large earthquakes.

### Challenges

The group will need to be aware of the data's temporal and spatial resolution. Gravity changes vary across different time scales and spatial ranges, impacting your analysis. There will also be seismic noise, specifically for the Tohoku-Oki Earthquake data.

### Contributions

- Kaitlyn: Mainly focused on analyzing the Lushan Earthquake. Found research paper and data, opened and parsed the data, and developed two figures to show findings about the research paper. Contributed to the developement and presentation of the research video.

- Bianca: Focused on the analysis of the Tohoku-Oki Earthquake. This included researching the earthquake, exploring and visualizing the data, and developing three figures aimed to help show the findings of the research. Also helped develope and present the research video.

### References:
Tohoku-Oki / Sendai Earthquake Gravity Field Changes:
[1] J.-P. Montagner et al., “Prompt gravity signal induced by the 2011 Tohoku-Oki earthquake,” Nature News, https://www.nature.com/articles/ncomms13349 (accessed Apr. 1, 2024).

Gravity Field Changes before 2013 Lushan Earthquake:
[2] L. Wang et al., “Gravity field changes reveal deep mass transfer before and after the 2013 Lushan earthquake,” Nature News, https://www.nature.

How Earthquakes Deform Gravity:
[3] “How earthquakes deform gravity,” Phys.org, https://phys.org/news/2020-02-earthquakes-deform-gravity.html (accessed Mar. 27, 2024.

