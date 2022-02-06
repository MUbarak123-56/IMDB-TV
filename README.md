# IMDb TV Series Project

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



## Objective


## Coding Folders

The coding folders are webscraping-code/ and data-exploration-code/. 

In the webscraping-code folder, there are two coding files named tv-data-collection.ipynb and top1000_episodes_imdb.ipynb. The tv-data-collection.ipynb file contains the code that was used to extract all the top 250 TV shows on IMDb's data. This is crucial towards collecting data on the top 250 TV shows on IMDb. The top1000_episodes_imdb.ipynb file was used to extract information of the top 1000 episodes on IMDb so they can be used to figure out which TV shows produce the best episodes on IMDb. 

Under the data-exploration-code/ folder, the data_exploration.ipynb file was used to explore the TV show data sets to extract crucial findings about the TV shows.

## Dataset Folders

There are three dataset folders: tv-series-data/, tv-series-data-named/ and cumulative-data/. 

The tv-series-data/ folder contains 250 data sets. Each dataset contains information about all the episodes' information of a specific TV show that belongs to the top 250 rated TV shows on IMDb. The data sets are named based on their encoded title which is of the format tt_______.csv. The blanks signifies the numbers that are used to act as an identifier for each TV show when searching for them on IMDb. Hence, if one were interested in accessing a TV show's page on IMDb, they can easily use the link: https://www.imdb.com/title/tt______/. All they need to do is to replace the tt______ in the link with the one that is used to store the TV show data sets' csv file.

The tv-series-data-named/ folder has the 250 data sets from the tv-series-data/ folder named appropriately with the actual TV show's name. This makes it easy for people who are interested in gathering specific information about a specific TV show.

The cumulative-data/ folder contains three data sets. The IMDb_top_250.csv file collects data on the top 250 rated IMDb TV show, their ratings and a few other information. The tv_dataset.csv is a concatenation of all the 250 datasets in tv-series-data/ folder. The top1000_episodes_imdb.csv file contains information about the top 1000 episodes of IMDb such as episode name, the TV show they belong to and other sorts of information about the episodes.

### Note about data

- It was noticed that some Attack on Titan episodes' airdates for season 1 are not chronological. This stems from the fact that the some of the airdates are the english airdate rather than the japanese airdate. Due to the fact that it takes a while to convert an anime from its original language into an english version, the airdates of the same episode tend to be wide apart for both languages. This phenomenon may be observed for other animes as well.

## Resources
- [Link to Top 250 TV shows on IMDb](https://www.imdb.com/chart/toptv/)
- [Link to Top 1000 TV series episodes on IMDb](https://www.imdb.com/search/title/?num_votes=1000,&sort=user_rating,desc&title_type=tv_episode)

## Tools and Technologies
- Python
- Jupyter Notebooks

## Contact Info
- Mubarak Ganiyu (mubarak.a.ganiyu@vanderbilt.edu)
