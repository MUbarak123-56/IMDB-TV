# IMDb Project

## Directory
- [Introduction](#introduction)
- [Objective](#objective)
- [Coding Folders](#coding-folders)
- [Dataset Folders](#dataset-folders)
- [Note About Data](#note-about-data)
- [Resources](#resources)
- [Tools and Technologies](#tools-and-technologies)
- [Contact](#contact-info)

## Introduction

Attack on Titan has rocked the world of anime ever since it debuted in 2013. It has left its viewers im awe by creating a mystery about the existence of titans who love to consume humans. In order to protect themselves from the titans, humans have been forced to live behind wall for about 100 years. The plot of the show focuses on how humans strive to break free of this predicament as they work towards bringing down the titans. Each episode is geared towards providing its audience with the best form of storytelling ever as every scene acts as a foreshadowing for an event in a future or past episode. Attack on Titan is a show that brings forth a lot of unanswered questions, massive plot twists and action-fueled events. 

## Objective

The objective of this project is to showcase the magnificence of Attack on Titan in the anime community. Data on the best anime will be collected from IMDb to explore Attack on Titan episode ratings in comparison to other anime. The requirement for belonging to the best anime on IMDb are for an anime to have over 10,000 votes as well as belonging to the top 50 highest rated anime on the site. Moreover, subtitle data will be gathered to conduct sentiment analysis on the plot of the show, so each episode's or character's sentiments can be explored over the course of the show. The data gathered from IMDb can also be used to explore Attack on Titan's ratings by analyzing its ratings by episode and total votes by episodes. This will provide information about the progression of Attack on Titan's ratings and viewership over time.

## Coding Folders

The coding folders are webscraping-code/ and data-exploration-code/. 

In the webscraping-code folder, there are two coding files named anime-data-collection.ipynb and top1000_episodes_imdb.ipynb. The anime-data-collection.ipynb file contains the code that was used to extract all the top 50 animes on IMDb's data. This is crucial towards assessing how Attack on Titan fares compared to the best animes on IMDb. The top1000_episodes_imdb.ipynb file was used to extract information of the top 1000 episodes on IMDb so they can be used to figure out which animes produce the best episodes on IMDb. 

Under the data-exploration-code/ folder, the data_exploration.ipynb file was used to explore the anime data sets to extract crucial findings about Attack on Titan.

## Dataset Folders

There are three dataset folders: tv-series-data/, tv-series-data-named/ and cumulative-data/. 

The tv-series-data/ folder contains 250 data sets. Each dataset contains information about all the episodes' information of a specific TV show that belongs to the top 250 rated TV shows on IMDb. The data sets are named based on their encoded title which is of the format tt_______.csv. The blanks signifies the numbers that are used to act as an identifier for each TV show when searching for them on IMDb. Hence, if one were interested in accessing a TV show's page on IMDb, they can easily use the link: https://www.imdb.com/title/tt______/. All they need to do is to replace the tt______ in the link with the one that is used to store the TV show data sets' csv file.

The tv-series-data-named/ folder has the 250 data sets from the tv-series-data/ folder named appropriately with the actual TV show's name. This makes it easy for people who are interested in gathering specific information about a specific TV show.

The cumulative-data/ folder contains three data sets. The IMDb_top_250.csv file collects data on the top 250 rated IMDb TV show, their ratings and a few other information. The tv_dataset.csv is a concatenation of all the 250 datasets in tv-series-data/ folder. The top1000_episodes_imdb.csv file contains information about the top 1000 episodes of IMDb such as episode name, the tv show they belong to and other sorts of information about the episodes.

### Note about data

- It was noticed that some Attack on Titan episodes' airdates for season 1 are not chronological. This stems from the fact that the some of the airdates are the english airdate rather than the japanese airdate. Due to the fact that it takes a while to convert an anime from its original language into an english version, the airdates of the same episode tend to be wide apart for both languages.

## Resources
- [Link to Top 250 TV shows on IMDb](https://www.imdb.com/chart/toptv/)
- [Link to Top 1000 TV series episodes on IMDb](https://www.imdb.com/search/title/?num_votes=1000,&sort=user_rating,desc&title_type=tv_episode)

## Tools and Technologies
- Python
- Jupyter Notebooks

## Contact Info
- Mubarak Ganiyu (mubarak.a.ganiyu@vanderbilt.edu)
