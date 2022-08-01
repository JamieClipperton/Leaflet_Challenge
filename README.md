# Leaflet_Challenge
Leaflet Homework: Visualizing Data with Leaflet


![image](https://user-images.githubusercontent.com/101610081/182191542-88efffa1-4ddc-465d-9550-aa5f5fd9beb3.png)


Welcome to the United States Geological Survey, or USGS for short. The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. As a new hire, you will be helping them out with an exciting new project!
The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

This homework uses both html and JavaScript so be sure to add all the necessary files. These will be the main files to run for analysis.


Your Task

Level 1: Basic Visualization
Your first task is to visualize an earthquake data set.
![image](https://user-images.githubusercontent.com/101610081/182191879-b6704eb9-45a2-4d10-bdef-d45794d99888.png)


Get your data set

The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON Feed page and pick a data set to visualize. When you click on a data set, for example "All Earthquakes from the Past 7 Days", you will be given a JSON representation of that data. You will use the URL of this JSON to pull in the data for our visualization.



Import & Visualize the Data
Create a map using Leaflet that plots all of the earthquakes from your data set based on their longitude and latitude.


Your data markers should reflect the magnitude of the earthquake by their size and and depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger and earthquakes with greater depth should appear darker in color.





Include popups that provide additional information about the earthquake when a marker is clicked.


Create a legend that will provide context for your map data.
![image](https://user-images.githubusercontent.com/101610081/182191775-85325c82-78df-4f47-9014-da4f063bedfa.png)


Level 2: More Data (Optional)

The USGS wants you to plot a second data set on your map to illustrate the relationship between tectonic plates and seismic activity. You will need to pull in a second data set and visualize it alongside your original set of data. Data on tectonic plates can be found at https://github.com/fraxen/tectonicplates.
In this step, you will:


Plot a second data set on our map.


Add a number of base maps to choose from as well as separate out our two different data sets into overlays that can be turned on and off independently.


Add layer controls to our map.
![image](https://user-images.githubusercontent.com/101610081/182192056-19993243-e9d1-404b-a4ee-892a7fb44827.png)




