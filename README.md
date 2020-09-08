# MrBouke Youtube Statistics
## About
This is a notesbook that looks at Machine Learning youtuber, Daniel Bourke's channel. The aim is to analyse the views of his videos about machine learning compared to fitness to see what is most popular.
## Required libraries
- pandas 1.1
- numpy 1.19.1
- matplotlib 3.2.2
- seaborn 0.10.2
- requests 2.24.0
- os
- math
- re 2.2.1
- datetime
- setAPIkey.py is a short code I created to set the API key as an environment variable.
## setAPIkey.py
```python
#!python3
# setAPIkey.py - Sets API key as an environment variable
# IMPORTANT: this must not be shared and is kept in .gitignore 

import os

os.environ['YT_API'] = '' # ENTER API KEY HERE
```
## Feedback
I would love any feedback. Please get in touch.