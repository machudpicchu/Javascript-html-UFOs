# Processing UFO Data Using JavaScript
## Overview of the analysis
In this module, we have been working with Dana, a data journalist, to create a webpage to filter data pertaining to UFOs.  The page is designed to take a large dataset stored in a JavaScript array and display it as a table that can be filtered according to user input in order to provide a more in-depth analysis of UFO sightings for visitors to the site.

## Results
The webpage was successfully created to display multiple filters alongside the table, allowing the user to input search elements that will filter the data for the reader to explore the data in a manageable way.
Here is an image of the website header.
![Website header](https://github.com/machudpicchu/UFOs/blob/main/images/Website-Header-Text.png)
Here is the table without any filters, as the user sees it when first visiting the website.
![Unfiltered table](https://github.com/machudpicchu/UFOs/blob/main/images/Data-Table-Unfiltered.png)

### Completing a search
When a user visits the site, a search can be completed by creating typing the desired parameters and pressing **'Enter'**.
#### Sample search by city:
![Sample Filter by City](https://github.com/machudpicchu/UFOs/blob/main/images/Sample-Search-City.png)
#### Sample search by shape:
![Sample Filter by Shape](https://github.com/machudpicchu/UFOs/blob/main/images/Sample-Search-Shape.png)
#### Press 'Enter"
![Press Enter](https://github.com/machudpicchu/UFOs/blob/main/images/Press-Enter.jpg)
### Resetting a search
In order to reset the search parameters, simply clear all the fields and press 'Enter' again (see image above).

## Summary
### Drawbacks
The primary drawback to this webpage as it is designed is that its search filters are limited to exact searches as they are typed into the input interface.  For example, all of the rows in the default data display list the country as "us," signifying the United States of America.  In order to search for sightings in any other country, one would have to know how those countries are abbreviated in order to search for them.  Another example of this limitation would be that dates can only be searched by a complete date instead of a date range or by partial dates, including all sightings in a single year or all sightings in a single month across multiple years.

### Recommendations
#### Recommendation 1:
My first recommendation would be to create a more dynamic search function to address the drawback mentioned above in regards to searching for dates.  This more dynamic search would include filtering by partial dates, date ranges, etc. instead of by a complete date.  This could also be related to the duration column, allowing for users to easily find the longest and shortest durations of sightings.
#### Recommendation 2:
A second recommendation, also mentioned above, would be to create dropdown menus for the shape and country functions so that users can see the options available from the data instead of having to enter guess what may not be apparent from the unfiltered table.  Users may or may not be able to get search results from entering "saucer" instead of "circle," but a dropdown menu for the shape would help to clarify if that is possible.
