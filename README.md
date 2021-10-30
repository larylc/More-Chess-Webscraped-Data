## Under Construction...

## Introduction

This repository is where I will be posting some of the webscraped data sets from my projects. 3 of these data sets were produced from my ["Grandmaster B-Days and B-Dates" project](https://larylc.github.io/chess_birthday_project/).  

The last data set **all_grandmaster_bdates_bplaces_updated.csv** was created seperately. The methods used to acquire the geographic locations will not be shared anywhere for a few reasons. First, the methods for acquiring the data followed a similar procedure to 3 first data sets in terms of using string distances and fuzzyjoins to combine the original **all_grandmaster_bdates_bplaces.csv** with other geographic data sets. Second, although most of the geographic data was available online for free, 246 cities needed to be manually inserted into the dataset to complete it. Finally, some corrections were made to the original data set to accomodate these updates. 

## Data 

Descriptions for original data sets:
* [all_grandmaster_bdates_bplaces.csv](https://github.com/larylc/More-Chess-Webscraped-Data/blob/main/all_grandmaster_bdates_bplaces.csv): Data set of all grandmaster `birthdates` and `city of birth` information as of September 2021.
* [rest_of_grandmaster_bdates_bplaces.csv](https://github.com/larylc/More-Chess-Webscraped-Data/blob/main/rest_of_grandmaster_bdates_bplaces.csv): Data set of grandmaster `birthdates` and `city of birth` information for chess players under 2600 as of September 2021.
* [top_grandmaster_ratings_before_2000](https://github.com/larylc/More-Chess-Webscraped-Data/blob/main/top_grandmaster_ratings_before_2000.csv): Data set of grandmaster `birthdates` and `city of birth` information for chess players over 2600 as of September 2021.


Descriptions for updated data sets:
* [all_grandmaster_bdates_bplaces_updated.csv](https://github.com/larylc/More-Chess-Webscraped-Data/blob/main/all_grandmaster_bdates_bplaces_updated.csv): Data set of grandmaster `birthdates` and `city of birth` information updated so that it includes `longitude`, `latitude` and `country of birth` information.


## Sources

You can visit the ["Grandmaster B-Days and B-Dates" project](https://larylc.github.io/chess_birthday_project/) original birthplace and city of birth sources. 

The geographic data was gathered from two main sources Google and the Simplemaps website. 

I could only download the free version of the US cities and world cities databases:
* [US cities](https://simplemaps.com/data/us-cities)
* [World Cities](https://simplemaps.com/data/world-cities)

From Google's Develeper site I got US state and country data:
* [US states](https://developers.google.com/public-data/docs/canonical/states_csv)
* [Countries](https://developers.google.com/public-data/docs/canonical/countries_csv)

Because Google does not allow you to scrape their geographic data, I had to manually get the last 246 by manually copy and pasting google searches. 




