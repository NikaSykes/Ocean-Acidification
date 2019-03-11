# Ocean-Acidification

# Introduction
This was a final project for an ocean engineering class. 
The scientific question this project asks is: 
Is there a more noticeable difference in ocean acidification at different locations of the ocean?

In order to investigate this question, real world data from various locations was used. 
This project compares the average pH levels at four different locations, US east coast, US west coast, Hawaii and Bay of Bengal. 

# Software Needed
This project was done using Jupyter notebook (Python 3 version), launched from Anaconda Navigator.

# Data
The data used for this project is from the NOAA website.
For general data searches: 
https://www.nodc.noaa.gov/oads/stewardship/data_portal.html?subpred=oads&varpred=any&geovars=pH&term=florida&obscat=Any&westbc=-180&northbc=90&southbc=-90&eastbc=180 

Using this search engine, I selected my search criteria to be pH. 
From these, I selected three resulting cases that were in different locations. 
The specific data used for this project can be found at the following links. 
At these pages, I clicked on download data and selected one .csv data file to use for each location. 
East coast: https://www.nodc.noaa.gov/ocads/data/0144340.xml 
West coast: https://www.nodc.noaa.gov/oads/data/0123467.xml
Honolulu, Hawaii: https://www.nodc.noaa.gov/oads/data/0132048.xml 
Bay of Bengal: https://www.nodc.noaa.gov/ocads/data/0162473.xml  

The specific data files I use for this project are also included in the file sections of this repository.

# Analysis and Results
For this project the pH levels were plotted to see the range of the pH levels at each location. 
The average pH level at each location was calculated for comparison between locations.
Sample of the results: the pH levels recorded for the West coast data:
pH average:
7.5637305825242676
pH range:
[7.218, 8.203]

A special note: for data used in this project there were some readings of pH at -999. pH levels can not be lower than 0. 
These can be presumed to have be outliers and needed to be removed to not skew the data. 
This was done by setting up a for loop that remove any negative numbers from the original data, and returns a new data set with only positive numbers.

