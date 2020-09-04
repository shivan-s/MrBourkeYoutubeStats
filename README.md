# MrBouke Youtube Statistics
## About
This is a notesbook that looks at Machine Learning youtuber, Daniel Bourke's channel. The aim is to analyse the views of his videos about machine learning compared to fitness to see what is most popular.
## What you need to do
- various libraries to install... coming soon
- setAPIkey.py is a short code I created to set the API key as an environment variable.
## setAPIkey.py
```python
#!python3
# setAPIkey.py - Sets API key as an environment variable
# IMPORTANT: this must not be shared and is kept in .gitignore 

import os

os.environ['YT_API'] = '' # ENTER API KEY HERE
```