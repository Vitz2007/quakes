# quakes
analysis on earthquake frequency


# Earthquake Analysis in US (1970-2014)

#### -- Project Status: [Completed]


## Project Intro/Objective
The purpose of this project is to analyze the range of magnitudes for earthquakes in the US and which states showed the most activity in the last decade (2004-2014).


### Methods Used
* Data Visualization


### Technologies
* Jupyter
* Python
* Pandas
* Numpy
* Matplot
* Plotly


## Project Description
Earthquake data can be extracted from [USGS](https://earthquake.usgs.gov/earthquakes/search/), but for the US, each state won’t correspond to the data pulled. As a result, in my searches I came across a notebook [Analyzing State-by-State Changes in Earthquake Frequency](https://nbviewer.jupyter.org/github/buzzfeednews/2015-03-earthquake-maps/blob/master/notebooks/earthquake-state-analysis.ipynb) through BuzzFeed News that had earthquake data filtered through PostGIS and matched data with each state in the US.
Growing up in California, earthquakes were a common occurrence for me, especially the Loma Prieta quake in 1989. I was curious to find out which months were more prone to having earthquakes, what other states besides California had frequent earthquakes, and taking the data a little further than the above notebook. 
In order to show magnitudes of earthquakes for states, I decided to utilize Plotly. Plotly has a steep learning curve and this was the biggest obstacle I faced working through this data and load times making sure plots lines up in correct states. 


## Needs of this project
- data exploration
- data cleaning
