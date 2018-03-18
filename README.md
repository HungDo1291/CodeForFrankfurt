# CodeForFrankfurt
Monitor Air Quality around Frankfurt. 
Input is a json file that contains sensor position, and 2 values of dust particle.
At the moment only the first value is used for visualization

The code use Leaflet.js map visualization, with marker cluster plugin.
Each cluster combines a number of sensors in that area. 
Each cluster marker displays the averaged sensor value. 
The color is coded simply as high(red) or low(green). 
Next step: get a continuous color scale. 



