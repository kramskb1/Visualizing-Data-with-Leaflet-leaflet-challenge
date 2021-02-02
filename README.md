	An earthquake data set was visualized. The USGS GeoJSON Feed Page was visited. I picked the data set “All Earthquakes from the Past 7 Days” to visualize. I was given a JSON representation of that data. I used the URL of this JSON to pull in the data for my visualization. 
	A map was created using Leaflet that plotted all of the earthquakes from the data set based on their longitude and latitude. The data markers reflected the magnitude of the earthquake by their size and depth of the earthquake by color. Earthquakes with higher magnitudes appeared larger. Earthquakes with greater depth appeared darker in color. The depth of the earth was found as the third coordinate of each earthquake. 
	Popups were included that provide additional information about the earthquake when a marker is clicked. A legend was created that provides context for the map data. I referred to leaflet documentation on how to create a legend. I included all css necessary for styling. I made sure that my map looked similar to the one given in the instructions.
	A function was defined to run once for each feature in the features array. A Leaflet legend was added using the map function. A button was added on the leaflet map. A control button was added on the leaflet map. A bind popup was used in my code to give each feature a popup describing the time and the place of the earthquake. Part of my code was used to magnify the magnitude. The last part of my code was used to loop through density intervals and generate a label with a colored square for each interval. 
	I learned a lot about using Leaflet while completing this assignment. I enjoyed working with earthquake data from the United States Geological Survey. I think it is a very useful skill to create a map using Leaflet of earthquakes based on their latitude and longitude. Visualizing a data set like this may be something that I will have to do in a future career of mine. I feel like completing this assignment makes me proficient in using Leaflet. 
