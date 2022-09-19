
# **Building And Deploying A Netflix Recommender System On Heruko**

![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg)
![HTML 4.01](https://img.shields.io/badge/HTML-4.01-skyblue.svg)
![CSS3](https://img.shields.io/badge/CSS3-pink.svg)
![sklearn](https://img.shields.io/badge/Library-sklearn-orange.svg)
![Numpy](https://img.shields.io/badge/Library-Numpy-blue.svg)
![flask](https://img.shields.io/badge/Library-flask-white.svg)
![Pandas](https://img.shields.io/badge/Library-Pandas-red.svg)

Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API.

used web scraping to get the reviews given by the user in the IMDB site using beautifulsoup4 and performed sentiment analysis on those reviews.
## Authors

- [@Akash Kumar Jha](https://github.com/Akash1070)

## Running Flask Api

To run tests, run the following command

```bash
  python app.py
```

## Running Heroku Tests

To run a Heroku deployment tests, click on the following link:

[Netflix Recommender System App](https://netflix-recommendation-system7.herokuapp.com/)

## Deployment

    1. Data Extraction
    2. Exploratory Data Analysis(EDA)
    3. Feature Engineering
    4. Model Building and Tuning
    5. Building Flask API
    6. Pushing code to Github
    7. Connecting to your Heroku account 
    8. Deploy App


## Installation

To install the libraries used in this project. Follow the 
below steps:

```bash
import numpy as np
import pandas as pd
from flask import Flask, render_template, request
from sklearn.feature_extraction.text import CountVectorizer
from sklearn.metrics.pairwise import cosine_similarity
import json
import bs4 as bs
import urllib.request
import pickle
import requests

```
## Demo

[Click HERE To View App](https://netflix-recommendation-system7.herokuapp.com/)

## Screenshot
![Click HERE To View](https://github.com/Akash1070/Deploying-a-Netflix-Recommender-System-on-Heroku-Cloud/blob/main/Preview.png)


## 🚀 About Me

Data Scientist Enthusiast | Petroleum Engineer Graduate | Solving Problems Using Data 


# Hi, I'm Akash! 👋


## 🔗 Links
[![github](https://img.shields.io/badge/github-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/Akash1070)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akashkumar107/)
## Tech stack
![Logo](https://businesstoys.in/assets/programs/full-stack-data-science-professional-program/tools.png)


## Other Common Github Profile Sections
👩‍💻 I’m interested in Petroleum Engineering

🧠 I’m currently learning Data Scientist | Data Analytics | Business Analytics

👯‍♀️ I’m looking to collaborate on Ideas & Data




## 🛠 Skills
1. Data Scientist
2. Data Analyst
3. Business Analyst
4. Machine Learning 


## Future Plans 

⚡️ Looking forward to help drive innovations into your company as a Data Scientist

⚡️ Looking forward to offer more than I take and leave the place better than i found
