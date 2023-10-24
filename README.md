# Isochrone of Milan's Infrastructure 🗺️🚲🚋

_"An isochrone map in urban planning is a map that depicts the area accessible from a point within a certain time/distance threshold."_

In this project, I create isochrones of various types of infrastructure in my hometown, Milan.
I began with the city's infamous new bikeways, but I plan on expanding it to bike sharing stations, metro stations, hospitals, and many more.

Information about Milan's infrastructure is freely available online on Comune di Milano's website (https://dati.comune.milano.it/).
I combine it with the city’s street network from OpenStreetMap and use NetworkX to find the shortest route from each point in the city to the closest access to the infrasture.
I then plot the isochrone using Folium and Branca.

![image](https://github.com/enricoburi/Isochrone_Milan_Infrastructure/assets/77646195/0c81fad7-255f-4625-9568-7546e228e5c6)

(Original inspiration: https://betterprogramming.pub/creating-a-traveling-distance-map-for-a-whole-city-with-python-f2e063272832)
