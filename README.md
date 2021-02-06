# AirBnB-Asheville
This is a fairly simple python notebook that was create to analyze characteristics of Asheville Airbnb rentals during Christmas over 2019 and 2020.

## Installation
 Most of the standard libraries were used in the project including `numpy` and `pandas` for data management, `matplotlib` and `seaborn` for graphics, and `sklearn` for some linear regression.  Additionally, `json` and `folium` were used for some interactive maps.
 
 All data is obtained from the [InsideAirbnb](http://insideairbnb.com) web site for Asheville, North Carolina, United States.  
 
## Motivation
This notebook was created for the first assignment in the [Udacity Data Science nanodegree program](https://www.udacity.com/course/data-scientist-nanodegree--nd025).  Our family decided to visit Asheville over the Christmas holidays in 2020 (maily to see the [Biltmore House](https://www.biltmore.com/things-to-do/events/christmas/)), but also to do some hiking.  We always enjoy staying in an AirBnB wherever we travel, so I was curious to see how the rental landscape in Asheville during Christmas changed from the pre-pandemic days of 2019 to 2020.

The questions I was most interested in were:
* How many properties are listed by neighborhood year over year?
* What is the average rental price of the listed properties listed by neighborhood year over year?
* What is the average rental price per maximum occupancy of the properties listed by neighborhood year over year?
* How has the relative availability changed over the given time period for each of the neighborhoods year over year?
* Did the most influential factors that determine price change year over year?

## File Descriptions
The files in the project include:
* Notebooks - AirBnbAsheville.ipynb
* Data - Includes calendar and listing files that were compiled on 24 October, 2020 and 27 October, 2019.  A .geojson was also loaded from the site that was used to draw the eight Asheville neighforgood districts.
* Results - This includes the various graphical output that was used in the associated Medium blog post.

## Findings
The number of Christmas-time listings decreased from 2019 to 2020, which given the pandemic, was not surprising.  What was interesting to see is that the rental prices increased year over year and the availability relatively decreased year over year, indicated demand did not suffer at the same level that supply did.  Additional comments and details can be found in the associated [blog post]().

## Acknowledgements
I definitely need to ackowledge [Udacity](http://udacity.com) and their Data Science nanodegree program which has forced :) me to learn how to use Git and Github and how to write a ReadMe file and how to write a blog post.  I would also like to acknowledge [Inside Airbnb](http://insideairbnb.com) for providing the data that was used for this project.
