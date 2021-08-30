# Mission-to-Mars


![img](CandidInfiniteElephantbeetle-mobile.gif)
##### source:https://gfycat.com/candidinfiniteelephantbeetle

## Overview
Robin wants to have a website with the latest information about Mars. For this reason, I created a web application that scrapes various websites for data related to the Mission to Mars and displays the information on a single HTML page. 

## Results

Mars Hemispheres

-I visited the Mars hemispheres site to obtain high-resolution images for each hemisphere.

-Save both the image URL string for the full resolution hemisphere image and the Hemisphere title containing the hemisphere name.

-I add the dictionary with the image URL string and the hemisphere title to a list. As result, this list contains one dictionary for each hemisphere
![img](https://github.com/Edgarhv/Mission-to-Mars/blob/d3ef969593e75456956aa28d90ec3273d1bc11ff/Mars%20Hemisphere%20Images.png)


I used MongoDB with Flask templating to create a new HTML page that displays all of the information that was scraped from the URLs above. I stored the return value in Mongo as a Python Dictionary. Also, I created a root route / that will query the Mongo database and pass the Mars Data into an HTML template to display the data. Finally, I created a template HTML file called index.html that will take the Mars Data Dictionary and display all of the data in the appropriate HTML elements.
![img](https://github.com/Edgarhv/Mission-to-Mars/blob/b43ac1c8db35367dcef58559f21dc3e625d0a761/html%20PAGE.png)
