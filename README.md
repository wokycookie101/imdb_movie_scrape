# Overview

Datascraping is a tool that not a lot of people may know about. I sure didn't, anyway, until I researched it for this module. This is yet another personal program that I developed for myself, since I'm a bit of a movie buff. I love foreign movies, and being the database nerd that I am, I decided I want to try creating a python program that'll datascrape the highest rated foreign movies currently on IMDb, and then paste the information into an Excel sheet. Currently, this program will scrape 100 entries. 

[Here's my software demo video!](https://youtu.be/3rfbWZFxoPQ)

# Data Analysis Results

My first question was: What are the top rated foreign movies on IMDb? Therefore, I created a python program that'll datascrape all of the highest rated foreign movies on IMDb, and paste that database into an excel sheet. 

My second question was: How many of those foreign movies are dramas? I noticed a trend with foreign movies that a lot of them are dramas, and I'm curious if that's the most common genre outside of america.

# Development Environment

I used the BeautifulSoup, Requests, and Openpyxl.

I also used Python as the main programming language here. 

# Useful Websites

{Make a list of websites that you found helpful in this project}
* [Python Webpage](https://www.python.org/)
* [Beautiful Soup Webpage](https://beautiful-soup-4.readthedocs.io/en/latest/)
* [Requests Tutorial Page](https://www.w3schools.com/python/module_requests.asp)
* [OpenXML Tutorial Page](https://openpyxl.readthedocs.io/en/stable/)

# Future Work
This is only a rough idea of what I want my program to do. Things that I will add in the future will include:
* Trying to implement an age-rating column (some of these movies are not rated, so I would run into an error whenever I would try to add one.)
* This only datascrapes one page, I'd like to actually scrape the whole database of IMDb sometime in the future. 
* Maybe I could make this into a general foreign movie data scraper tool. 
