# Overview
The UFO sightings data shows that there are a vast number of sighting across the world. Users would like to be able to filter these sightings by date, city, state, country, and shape. As the user updates the filters the page will dynamically update the table on the right.

# Results
The completed webpage allows users to filter based on various categories. The filters are additive so the users can quickly get to the results they want.
See the directions below on how to use the filters.
## Directions to filter results
1. Filter options can be found on the left side of the page. You may need to scroll down to find see the filters.
![Filters](../main/resources/filters_start.png)
2. Click in to the first box that you want to filter
3. In the desired field, enter in the text you want to search for. NOTE: For the date, you will need to enter the date in the format of "01/01/2001". Below is an example of filtering by city
![City Filter](../main/resources/city.png)
4. The filter will be applied when you click out of the box or press enter.
5. You can apply multiple filters by filling in mutliple fields.
![Mutliple Filters](../main/resources/multiple.png)


# Summary
## Drawback
This webpage is a great store in sharing UFO sighting data. The data set used in the table is a static list and requires would require a manual update of the entire data set that is stored in the data.js file. It would be better to have the data in a database so the sightings can be easily be added and in turn displayed on the website.
## Future Development
There are a couple opportunities for future refinement of the webpage and its filters.
1. Date filter - One improvement to the date filter would be to have a date picker rather than requiring the user to enter in the date. This would eliminate the possibility of miskeying a date and getting no results when the filter is applied.
2. Filters work regardless of case of text - Ensuring that the filters work regardless if the user capitalizing the names of cities or state/coutnries would be a great addition. This would ensure that the users are able to get to the desired data quickly. 
