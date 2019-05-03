# CodeForFrankfurt
Monitor Air Quality around Frankfurt. 

Input is a json file that contains the position of sensors and the level of dangerous particles.

The code use Leaflet.js map visualization, with marker cluster plugin.

The air quality is coded to a discrete scale of 5 colors.

When the map is zoomed out, markers are clustered together showing the average value for that region.

Each cluster combines a number of sensors in that area and displays the averaged sensor value. 

End result before I left Germany is hosted here: data-automation.000webhostapp.com

It is interesting because you can scan the map to see which countries produce the most pollution.

The future work would be a server and a database that update the json file in real-time.

