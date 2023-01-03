# Population, Crime, & Starbucks

## Table of contents
* [Motivation](#motivation)

* [Data Question](#data-question)

* [The Starbucks Effect](#the-starbucks-effect)

* [Technologies](#technologies)

* [The Process](#the-process)

* [Link to website](#link-to-website)

## Motivation
Life itself has always been my greatest motivator. My experiences make me who I am, and they are also what inspired this project.  I was staying with my aunt and she had a pretty bad cold. So, of course I think, "She needs a medicine ball from Starbucks." I proceed to GPS for the closest location, and to my surprise, there were no locations within a 10-15 mile radius. I found this very surprising considering she lives relatively close to downtown Nashville, and off of a main road close to a major  highway. I also considered that she doesn't live in the nicest neighborhood either. A lot of thoughts went through my mind. Maybe it's  the data analyst in me, whatever it was, it  drove me to want to take a closer look at what could really be the cause.

## The Starbucks Effect
#### What is the Starbucks Effect?

 According to [Investment Properties American](https://aipcommercialrealestate.com/the-starbucks-effect/#:~:text=The%20Starbucks%20Effect%20on%20Local%20Real%20Estate%20and,developers%20that%20the%20neighborhood%20is%20on%20the%20rise.), "A Starbucks location can have a huge effect on the neighborhoods that surround them. This is known as the 'Starbucks effect'. In fact, there has been a lot of research conducted to prove that Starbucks is a positive indicator of thriving real estate values by Zillow CEO Spencer Rascoff and Chief Economist Stan Humphries in the New York Times bestseller "Zillow Talk: Rewriting the Rules of Real Estate." [Harvard Business Review](https://hbr.org/2000/03/the-starbucks-effect) even chimed in and provided insight into the "Starbucks effect" impacting the marketplace stating, "The success of Starbucks cafés has been good for coffee distributors all over the United States."​What about crime though?


## Data Question
Can Starbucks locations serve as indicators for levels of crime and/or population?

## Technologies
<details>
  <summary>Click me</summary>

  #### Python
     * Selenium Webdriver
     * WebdriverWait
     * BeautifulSoup
     * Geopandas
     * Shapely.geometry
     * Folium

  #### Microsoft Excel


</details>

## The Process
#### Scrape
Much of the ground work for this project was using Python(pandas, request, selenium) to scrape [Starbucks](https://www.starbucks.com/store-locator?map=36.62577,-87.31855,15z) for store locations in Davidson County.


#### Challenges
The dynamic web scrape was one of my biggest challenges. Aside from that there were some additional challenges getting the geometry correct so that it could be using geopandas.

## Link to Website
https://xxiv7pr.wixsite.com/data-news-nashville/coming-soon-03
