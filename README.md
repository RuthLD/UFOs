# UFOs
👽 Use JavaScript to create a dynamic webpage for UFO sighting data.
## Overview: 
This analysis aimed to view information related to UFO sightings based on five search criteria.
1. Date 📅
1. City 🏙️
1. State 🗽
1. Country 🗺️
1. Type 🔵


The information is displayed on a webpage that accepts user input for any combination of the search criteria. The UFO data is pulled from the [data.js](https://github.com/RuthLD/UFOs/blob/main/static/js/data.js) file, well [app.js](https://github.com/RuthLD/UFOs/blob/main/static/js/app.js) holds the code for the filters, and the [index.html](https://github.com/RuthLD/UFOs/blob/main/index.html) holds the webpage code.

## Using the Webpage: 
The filters to search by are located below the introduction to the webpage.
![Enter_site.gif](https://github.com/RuthLD/UFOs/blob/main/Resources/Enter_site.gif)
* Use the "Date" filter, type a date in the mm/dd/yyyy format into the box, and then click outside the box to update the table.
 * ![input_date.gif](https://github.com/RuthLD/UFOs/blob/main/Resources/input_date.gif)
* Use the "City" filter, type a city's name in lowercase into the box, then click outside the box to update the table.
 * ![input_city.gif](https://github.com/RuthLD/UFOs/blob/main/Resources/input_city.gif)
* Use the "State" filter, type the two-letter abbreviation of a state in the United States in lowercase into the box, then click outside the box to update the table.
 * ![input_state.gif](https://github.com/RuthLD/UFOs/blob/main/Resources/input_state.gif)
* Use the "Country" filter, type the two-letter abbreviation of a country using lowercase into the box, and then click outside the box to update the table.
 * ![input_country.gif](https://github.com/RuthLD/UFOs/blob/main/Resources/input_country.gif)
* To use the "Type" filter, type a shape name like "triangle" or "circle" into the box using lowercase, then click outside the box to update the table.
 * ![input_shape.gif](https://github.com/RuthLD/UFOs/blob/main/Resources/input_shape.gif)
* To use multiple filters, follow the instructions for each of the search criteria in any order, one after the other. You will see the table update with each filter added.
 * ![multi_input.gif](https://github.com/RuthLD/UFOs/blob/main/Resources/multi_input.gif)


If the table is empty, there is no data for the information inputted in the search criteria.
 
## Summary: 
One drawback of this design is that it did not explicitly state when the search criteria returned no results.


Two things that may be helpful for further development of the webpage are an error message when no results are found from the search and a more flexible date search that would allow for filtering by month or year instead of a specific date.
