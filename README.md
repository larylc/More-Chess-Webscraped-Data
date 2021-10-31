## Under Construction...

## Introduction

This repository is where I will be posting some of the webscraped data sets from my projects. The  3 `grandmaster_bdates_bplaces.csv files` were produced from my [Grandmaster B-Days and B-Dates project](https://larylc.github.io/chess_birthday_project/).  

The `top_grandmaster_ratings_before_2000.csv` was produced from the [Finding the Missing Records project](https://larylc.github.io/Independent-Projects-/missing_chess_records.html). 

The `all_grandmaster_bdates_bplaces_updated.csv` was created seperately. The methods used to acquire the geographic locations will not be shared anywhere for a few reasons. First, the methods for acquiring the data followed a similar procedure to 3 first data sets in terms of using string distances and fuzzyjoins to combine the original **all_grandmaster_bdates_bplaces.csv** with other geographic data sets. Second, although most of the geographic data was available online for free, 246 cities needed to be manually inserted into the dataset to complete it. Finally, some corrections were made to the original data set to accomodate these updates. 

The `all_prodigies.csv` was used to make [Pathway to Prodigy App](https://loganlary.shinyapps.io/prodigies_app/?_ga=2.15136438.103236738.1633010249-569369622.1613318148). It uses data from the `all_grandmaster_bdates_bplaces_updated.csv` , `top_grandmaster_ratings_before_2000.csv`, [`top_grandmasters_sept.csv`](https://github.com/larylc/Chess-Webscraping-Projects/blob/main/top_grandmasters_sept.csv),  and [`masters_table_2500s_sept.csv`](https://github.com/larylc/Chess-Webscraping-Projects/blob/main/masters_table_2500s_sept.csv).


## Data 

Descriptions for original birthdate and birthplace data sets:
* [all_grandmaster_bdates_bplaces.csv](https://github.com/larylc/More-Chess-Webscraped-Data/blob/main/all_grandmaster_bdates_bplaces.csv): Data set of all grandmaster `birthdates` and `city of birth` information as of September 2021.
* [rest_of_grandmaster_bdates_bplaces.csv](https://github.com/larylc/More-Chess-Webscraped-Data/blob/main/rest_of_grandmaster_bdates_bplaces.csv): Data set of grandmaster `birthdates` and `city of birth` information for chess players under 2600 as of September 2021.
* [top_grandmaster_bdates_bplaces.csv](https://github.com/larylc/More-Chess-Webscraped-Data/blob/main/top_grandmaster_ratings_before_2000.csv): Data set of grandmaster `birthdates` and `city of birth` information for chess players over 2600 as of September 2021.


Description for rating record data set:
* [top_grandmaster_ratings_before_2000](https://github.com/larylc/More-Chess-Webscraped-Data/blob/main/top_grandmaster_ratings_before_2000.csv): Data set of top grandmaster monthly classical ratings before January of 2000.

Description for updated birthdate and birthplace data set:
* [all_grandmaster_bdates_bplaces_updated.csv](https://github.com/larylc/More-Chess-Webscraped-Data/blob/main/all_grandmaster_bdates_bplaces_updated.csv): Data set of grandmaster `birthdates` and `city of birth` information updated so that it includes `longitude`, `latitude` and `country of birth` information.


## Sources

You can visit the [Grandmaster B-Days and B-Dates project](https://larylc.github.io/chess_birthday_project/) for the original birthplace and city of birth sources. 

You can visit the [Finding the Missing Records project](https://larylc.github.io/Independent-Projects-/missing_chess_records.html) for the rating records before 2000. 


The geographic data was gathered from two main sources Google and the Simplemaps website. 

I could only download the free version of the US cities and world cities databases:
* [US Cities](https://simplemaps.com/data/us-cities)
* [World Cities](https://simplemaps.com/data/world-cities)

From Google's Develeper site I got US states and country data:
* [US States](https://developers.google.com/public-data/docs/canonical/states_csv)
* [Countries](https://developers.google.com/public-data/docs/canonical/countries_csv)

Because Google does not allow you to scrape their geographic data, I had to manually get the last 246 by manually copy and pasting google searches. 



## Contact Me

|**Contact Method**  |                          |
| -------------------| -------------------------|
| Professional Email | cedric.lary1@gmail.com   |

