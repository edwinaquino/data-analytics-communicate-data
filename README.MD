# Project #4 - Communicate Data Project 
### Udacity Data Analyst Nanodegree

In this project, we will be gathering data from the Ford GoBike System. The goal for this project is to wrangle Ford GoBike System Data to create interesting and trustworthy analyses and visualizations.

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

On this data set we will be doing some data wrangling in order to make it tidy for analysis. There are multiple cities covered by the linked Ford GoBike System, and multiple data files will be joined together to compile all of 2017 & 2018.

This project is divided into two major parts. In the first part, we will conduct an exploratory data analysis on a dataset. We will using Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships. The analysis in this part will be structured, going from simple univariate relationships up through multivariate relationships. This project is our opportunity to ask questions of the data and make our own discoveries.

In the second part, we will take our main findings from this exploration and convey them to others through an explanatory analysis. To this end, we will create a slide deck that leverages polished, explanatory visualizations to communicate our results. This part of the project will make heavy use of the first part of the project. We will select one or two major paths in our exploration, choosing relevant visualizations along that path, and then polish them to construct a story for readers to understand what we found.

```python
# Include required libraries for this project
from os import path, getcwd, makedirs, listdir
from io import BytesIO # for zip files
from zipfile import ZipFile
import pandas as pd
import numpy as np
import matplotlib
from matplotlib import pyplot as plt
import matplotlib.ticker as tick
import seaborn as sns
import datetime
import time
import calendar
import warnings
import requests
from pathlib import Path
#warnings.filterwarnings('ignore') - only show errors
from IPython.display import Image
%matplotlib inline
import warnings
warnings.filterwarnings('ignore')
# Display progress bar
from ipywidgets import FloatProgress
from IPython.display import display, clear_output
```

## First Part
[Ford GoBike System (Lyft) Data Project](https://edwinaquino.github.io/data-analytics-communicate-data/Bike_Share_Part1_Exploratory.html)

## Second Part
[Bike Sharing Trends of Ford GoBike System](https://edwinaquino.github.io/data-analytics-communicate-data/Bike_Share_Part2_Explanatory.html)

[Bike Sharing Trends of Ford GoBike System Slides](https://edwinaquino.github.io/data-analytics-communicate-data/Bike_Share_Part2_Explanatory.slides.html)


