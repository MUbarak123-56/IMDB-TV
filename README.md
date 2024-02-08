# IMDb TV Series Project
[![View on Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)](https://public.tableau.com/app/profile/mubarak.ganiyu/viz/IMDbTVShowAnalysis/Top10TVshowsonIMDb-Ratings)

## Directory
- [Background and Objective](#background-and-objective)
- [Coding Folders](#coding-folders)
- [Dataset Folders](#dataset-folders)
- [Note About Data](#note-about-data)
- [Resources](#resources)
- [Tools and Technologies](#tools-and-technologies)
- [Contact](#contact-info)

## Background and Objective

IMDB hosts a lot of information about TV shows and movies. It is a web platform that is information rich in terms of details about movies, TV shows or mini-series. The information it has about the movies/TVshows are about the airdate, ratings, descritpion, director, et al. In case of TV shows, it also has information about each episode. Due to its neat setup, IMDb is ripe for data collection. Hence, it is easy to create a data set on the TV shows on IMDb. A lot of people often hype up their favorite TV shows on a weekly basis, and it would be great to actually examine how these shows perform in comparison to one another. Hence, the objective of this project is to collect data on the episodes of all the TV shows in the top 250 TV shows on IMDb. Then, to proceed to analyze them to extract insights on how they perform.

## Coding Folders

The coding folders are webscraping-code/ and data-exploration-code/. 

In the webscraping-code folder, there are two coding files named tv-data-collection.ipynb and top1000_episodes_imdb.ipynb. The tv-data-collection.ipynb file contains the code that was used to extract all the top 250 TV shows on IMDb's data. This is crucial towards collecting data on the top 250 TV shows on IMDb. The top1000_episodes_imdb.ipynb file was used to extract information of the top 1000 episodes on IMDb so they can be used to figure out which TV shows produce the best episodes on IMDb. 

Under the data-exploration-code/ folder, the data_exploration.ipynb file was used to explore the TV show data sets to extract crucial findings about the TV shows.

## Dataset Folders

There are three dataset folders: tv-series-data/, tv-series-data-named/ and cumulative-data/. 

The tv-series-data/ folder contains 250 data sets. Each dataset contains information about all the episodes' information of a specific TV show that belongs to the top 250 rated TV shows on IMDb. The data sets are named based on their encoded title which is of the format tt_______.csv. The blanks signifies the numbers that are used to act as an identifier for each TV show when searching for them on IMDb. Hence, if one were interested in accessing a TV show's page on IMDb, they can easily use the link: https://www.imdb.com/title/tt______/. All they need to do is to replace the tt______ in the link with the one that is used to store the TV show data sets' csv file.

The tv-series-data-named/ folder has the 250 data sets from the tv-series-data/ folder named appropriately with the actual TV show's name. This makes it easy for people who are interested in gathering specific information about a specific TV show.

The cumulative-data/ folder contains three data sets. The IMDb_top_250.csv file collects data on the top 250 rated IMDb TV show, their ratings and a few other information. The tv_dataset.csv is a concatenation of all the 250 datasets in tv-series-data/ folder. The top1000_episodes_imdb.csv file contains information about the top 1000 episodes of IMDb such as episode name, the TV show they belong to and other sorts of information about the episodes.

The data-for-charts/ folder contains data sets that were used to build dashboards on Tableau. The dashboards are currently hosted live on Tableau Public through this [link](https://public.tableau.com/views/IMDbTVShowAnalysis/Top10TVshowsonIMDb-Ratings?:language=en-US&:display_count=n&:origin=viz_share_link).

All three datasets are currently presented [here](https://www.kaggle.com/muby98/imdb-tv-show-data-sets-top-250-tv-shows-on-imdb) on Kaggle.

### Note about data

- It was noticed that some Attack on Titan episodes' airdates for season 1 are not chronological. This stems from the fact that the some of the airdates are the english airdate rather than the japanese airdate. Due to the fact that it takes a while to convert an anime from its original language into an english version, the airdates of the same episode tend to be wide apart for both languages. This phenomenon may be observed for other animes as well.

## Resources
- [IMDb](https://www.imdb.com/)
- [Link to Top 250 TV shows on IMDb](https://www.imdb.com/chart/toptv/)
- [Link to Top 1000 TV series episodes on IMDb](https://www.imdb.com/search/title/?num_votes=1000,&sort=user_rating,desc&title_type=tv_episode)

## Tools and Technologies
- Python
- Jupyter Notebooks

## Contact Info
- Mubarak Ganiyu (ganiyubaraq@gmail.com)
