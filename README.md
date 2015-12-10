# Team Vulpix

![Team Vulpix](vulpix.png "Team Vulpix")

## CS109 Anime Analysis (Dylan, Kelwen, Tiffany, Le (Tuongvan))

### Motivation 

In the past several decades, anime has become widely popular in Western countries. Westerners interested in the culture of Japan would immediately know about Japanese anime. Anime enthusiasts have formed fan clubs and forums to share opinions and recommendations of anime music videos, new anime releases, and others. As anime became increasingly popular, websites such as myanimelist and anime-planet popped up to collect ratings and reviews of anime. As some of our team members are anime fans, we are interested in understanding how like-minded individuals rate and review anime. We want to look for trends in popularity of anime based on various factors such as genres, studios, number of episodes, etc. By developing a model to quantify these various factors’ contributions to the anime’s overall ratings and rankings, we will be able to predict the ratings and rankings of new release anime and suggest them to the general audience. In addition, as different users have different preferences and tastes, we also want to examine the users’ profiles and past reviews and develop personalized recommendations of anime for these users.


### Website

Our results and finding are summarized at [Team Vulpix's website](http://cs109-animeplanet.strikingly.com/)

### Video

Video summary of our process and findings [here](www.youtube.com)

### Github

Public directory of [Project](https://github.com/xjgege/vulpix)

#### data

Contains the csv data files used in for data analysis.

1. anime_info.csv: information about each anime found from anime-planet
2. all_reviews.csv: stores all reviews and ratings found on anime-planet
3. all_users.csv: contains publicly available user information

#### scraping

Contains ipython notebooks used to scrape anime and user information

#### analysis

Contains ipython notebooks used for exploratory analysis, modeling data, linear regression and classifiers, and text analysis

#### Libraries Used

1. numpy
2. pandas
3. scipy
4. matplotlib
5. requests
6. pickle
7. json
8. bs4
9. collections
