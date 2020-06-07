# Webmap with Folium
Python script that makes use of Folium library to create an interactive webmap for data presentation.

### Description
Script that creates a webmap with two layers. First layer is created using the **GeoJson** class from folium and present each country in the world with its frontiers and a specific colour based on its population, green for a population lower than 10 millions, orange for populations between 10 and 20 millions and red for population above 20 million.

![alt text](https://github.com/pedropenacho/Webmap-with-Folium/blob/master/Images/world%20map.png "World Map")

You can easily get the name and population of any country in the world by simple hovering the mouse in a specific country.

![alt text](https://github.com/pedropenacho/Webmap-with-Folium/blob/master/Images/hover%20mouse.png "Country data")

Our second layer displays markers that represent the location of the volcanoes in the USA. To access and interact with the markers in the map you need first to deselect the population layer by unticking "Population" on the top right hand corner of the map.

![alt text](https://github.com/pedropenacho/Webmap-with-Folium/blob/master/Images/USA%20Volcanoes.png "Volcanoes location")

After that you can have access to more data about any of the volcanoes by simple clicking your mouse on the markers. It should retrieve the name with a hyperlink for more information on that volcano and the volcano height in meters.

![alt text](https://github.com/pedropenacho/Webmap-with-Folium/blob/master/Images/volcono%20info.png "Volcano data")
