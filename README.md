# Stock-Web-Scrapping-and-Sentiment-Analysis

A sentiment analysis was carried out on the stock news. I sourced for data by scrapping a website on stock, https://finviz.com/. After the sentiment analysis, i created a visualization to show the average scores on each news for each day.
The first thing to do before scrapping the data, I imported the necessary libraries i will be using to carry out the project.

## Importing Libraries
from urllib.request import urlopen, Request
from bs4 import BeautifulSoup
from nltk.sentiment.vader import SentimentIntensityAnalyzer
import pandas as pd
import matplotlib.pyplot as plt
