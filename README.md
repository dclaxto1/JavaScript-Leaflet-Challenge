# JavaScript-Leaflet-Challenge   
### Background      
The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-usage change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.  

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, you have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

Instructions The instructions for this activity are broken into two parts: Part 1: Create the Earthquake Visualization Part 2: Gather and Plot More Data.    

## Part 1: Create the Earthquake Visualization    

Your first task is to visualize an earthquake dataset. Complete the following steps:   
  
Get your dataset. To do so, follow these steps:  

The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON FeedLinks to an external site. page and choose a dataset to visualize. When you click a dataset (such as "All Earthquakes from the Past 7 Days"), you will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualization. 
![image](https://github.com/dclaxto1/JavaScript-Leaflet-Challenge/assets/128431134/04329be3-5208-4377-8e0e-331f427c95ef)

Import and visualize the data by doing the following: Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude. Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color. Hint: The depth of the earth can be found as the third coordinate for each earthquake. Include popups that provide additional information about the earthquake when its associated marker is clicked. Create a legend that will provide context for your map data. Your visualization should look something like the preceding map.
![image](https://github.com/dclaxto1/JavaScript-Leaflet-Challenge/assets/128431134/64024f9b-4250-48c2-bf9e-2ef20d7498a8)


## Part 2: Gather and Plot More Data.
Plot a second dataset on your map to illustrate the relationship between tectonic plates and seismic activity. You will need to pull in this dataset and visualize it alongside your original data. Data on tectonic plates can be found at https://github.com/fraxen/tectonicplatesLinks to an external site.. This part is completely optional; you can complete this part as a way to challenge yourself and boost your new skills.

Perform the following tasks: Plot the tectonic plates dataset on the map in addition to the earthquakes. Add other base maps to choose from. Put each dataset into separate overlays that can be turned on and off independently. Add layer controls to your map.
![image](https://github.com/dclaxto1/JavaScript-Leaflet-Challenge/assets/128431134/d0a52c0a-d963-4aba-8224-befc54be57e2)

## Additional Features: 
I added a topological map layer that can be toggled on/off.
![image](https://github.com/dclaxto1/JavaScript-Leaflet-Challenge/assets/128431134/dbea2318-32be-47e8-9fa3-a87bbaa25e59)


# View Interactive Page:
https://dclaxto1.github.io/JavaScript-Leaflet-Challenge/
