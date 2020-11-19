# UFO_sightings

![surfsup](static/images/vectorstock_13480094.png)
*****
*****

* By: Tyler Sojka
* November 2020
* JavaScript: Using js to create tables, filter tables, event listeners to handle clicks and changes
  
*****
*****

## Overview

*****

The purpose of this analysis was to build a simple web page to showcase a dataset of UFO sighting data. We then used JavaScript to add functionality to the webpage. Using JS, we populated a table with all of our UFO sighting data, and added input boxes to allow filtering of the displayed entries based on the input criteria.

## Results

*****

To use the web page it is as easy as entering a value into one of the search fields. You can enter just one, or up to 5, and if there is an entry matching all searched for criteria, it will be displayed. To clear your searches, simply click the clear filters button and the filters will be cleared and the whole data set will be re-loaded. Below is a short video walking you through the process of entering filter criteria, and how to clear them.

![searchgif](static/images/ufo_screen_recording.gif)

## Summary

*****

### Drawback 1

One potential drawback of this webpage is its ability to refresh in real-time. Once you enter a search value, that value is an active filter until you refresh the page and reload the unfiltered table.

* **Solution 1**
  
  One solution, and perhaps the most simple to implement, would be to simply add a button that refreshes the webpage. Once clicked, the button refreshes the page, clearing all of the search criteria, and re-loading the un-filtered table. This has already been implemented in the project.

* **Solution 2**
  
  The second and slightly more complicated would be to make the filtering respond in real time with keyUp and keyDown listeners to respond with each character entered in each search box. This would allow a sort of reverse filtering if you wanted to keep your current search criteria but change one of the values.

* ### Drawback 2

Another drawback of this analysis is the scope of the data. The data set is quite small. We only have entries from January 2010, in the US.

* **Solution 1**

    One solution would be to contact whoever put together the original dataset. If they took the time to compile that first list, there is a good chance that they also might have more.

* **Solution 2**
  
    A second solution to the small dataset would be to source your own data. You could search the internet for databases of UFO sightings. Mufon.com has a database you can sign up to access. You could scrape that page, transform the data into a useable format and add it to our list. This option was found with 10 seconds of googling, a more thorough search would most likely result in more data.
