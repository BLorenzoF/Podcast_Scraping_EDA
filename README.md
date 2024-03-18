### Introduction
Python Project in 2 different parts

 ### 1st part.
 Scraping_Itunes_Podcasts.ipynb
 
 Scraping of Itunes to obtain a csv with different categories. This part of the code is taken and adapted from user Odenizgiz on [Github](https://github.com/odenizgiz/Podcasts-Data/blob/master/02.1%20Build%20the%20Dataset%20from%20iTunes%20Website.ipynb). First we scrape all the URLs from this [Itunes page](https://itunes.apple.com/us/genre/podcasts/id26?mt=2) which contains all the podcast genres. Then we scrapes each of these pages in turn to extract the links to each individual podcast page.
 
### 2nd part.
Podcasts_Exploratory_Data_Analysis
Performing a exploratory data analysis on the obtained CSV. With language detection the notebook cleans the characters not in english and make wordclouds of each genre. With NLP identifies person names and prepares the CSV for modelling.

### Purpose of the model: 
Predict the number of positive ratings of a podcast using all the info the csv currently has.
