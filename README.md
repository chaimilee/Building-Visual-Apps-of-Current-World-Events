# Building-Visual-Apps-of-Current-World-Events
Created a set of visualizations and plots to illustrate some of the current World events (as of April 2022). Used images of 3 news sources (CNN, Fox, and Aljazeera) as data. Built dynamic maps of the specific locations of interest by performing OCR on images of news sources. Explored and analyzed the entities appearing in the news, as well as their relation. Compared and contrasted various news sources and identify the key similarities and differences between them.

## Requirements

1) For Optical Character Recognition (OCR):

Install the following:
- pip install geopy
- pip install pytesseract
- sudo apt install tesseract-ocr
- sudo apt install libtesseract-dev
- pip install Pillow==9.0.0

Install the following libraries:
- import PIL
- from PIL import Image
- import pytesseract
- import os
- import re
- import string
- import nltk
- from collections import OrderedDict
- import json

2) For Named-Entity Recognition (NER):

Install the following libraries:
- import spacy
- import matplotlib.pyplot as plt
- import json
- from itertools import islice
- nlp = spacy.load("en_core_web_sm")

3) For Geoparsing/Building maps

Install the following:
- pip install geopy
- pip install plotly
- pip install geopandas
- pip install -U kaleido

Install the following libraries:
- import spacy
- from itertools import islice
- import plotly.graph_objects as go
- from geopy.geocoders import Nominatim
- from geopy.geocoders import Photon
- import kaleido

## Maps

Dynamic Map of Ukraine
![](https://github.com/chaimilee/Building-Visual-Apps-of-Current-World-Events/blob/main/ukraine_map_gif.gif)

Dynamic World Map

![](https://github.com/chaimilee/Building-Visual-Apps-of-Current-World-Events/blob/main/world_map_gif.gif)
