# Leaflet-Challenge
In this challenge, we have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

Instructions
The instructions for this activity are broken into two parts:
Part 1: Create the Earthquake Visualization
Part 2: Gather and Plot More Data 

Part 1: Create the Earthquake Visualization
1.Dataset - USGS earthquake data 
![Data](C:\Users\cghos\OneDrive\Desktop\leaflet-challenge\Leaflet-Part-1\Images\3-Data.png)
All Earthquakes from the Past 7 Days
The following image is a sampling of earthquake data in JSON format:
![JSON](JSON.jpg)
2.Import and visualize the data by doing the following:
Using Leaflet, created a map that plots all the earthquakes from the dataset based on their longitude and latitude.
The data markers  reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes appear larger, and earthquakes with greater depth appear darker in color.
Included popups that provide additional information about the earthquake when its associated marker is clicked.
Created a legend that will provide context for the map data.

Part 2: Gather and Plot More Data
Plotted a second dataset on my map to illustrate the relationship between tectonic plates and seismic activity. 
We pulled in this dataset and visualized it alongside the original data. 
Data on tectonic plates can be found at https://github.com/fraxen/tectonicplatesLinks.
    1. Plotted the tectonic plates dataset on the map in addition to the earthquakes.
    2. Added other base maps to choose from.
    3. Put each dataset into separate overlays that can be turned on and off independently.
    4. Added layer controls to our map.