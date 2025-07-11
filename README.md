# Melbourne Solar Adoption Analysis

This project examines the house features which influence solar adoption. I used the Melbourne house sales dataset and the Melbourne solar dataset, as well as the postcodes shapefile for mapping.

## Description

I process and clean the data, perform EDA and then use K-means clustering to group the datapoints into clusters. The clusters are then mapped using folium to find out what they represent. Once mapped it becomes clear that houses in older suburbs have less solar adoption which is likely due to the difficulty in installation and the need to preserve the character of old houses.

After I have made sense of the clusters I give them sensible names: older/newer inner suburbs and older/newer outer suburbs. I then perform a significance test, which shows that the difference in the mean of solar units installed is statistically significant. This validates the clustering

## Future Work
* Using more visualisations techniques (like a 3D map) with folium and other libraries to draw more insights.
* Adding more data from ABS - for example examining which demographic factors influence solar adoption.
* Use of different ML models for further analysis and to model solar adoption.
## Version History

* 0.1
    * Initial Release

