# Web Scraping and NLP with Requests, BeautifulSoup, and spaCy

Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

## Getting started

Fork (copy into your GitHub account) and clone down (to your machine) this repo to get started with web scraping.

## Install necessary dependencies
* Create and activate a Python virtual environment. 
* Before starting the project, try all these imports FIRST
* Address any errors you get running this code cell 
* by installing the necessary packages into your active Python environment.
* Try to resolve issues using your materials and the web.
* If that doesn't work, ask for help in the discussion forums.
* You can't complete the exercises until you import these - start early! 
* We also import pickle and Counter (included in the Python Standard Library).

from collections import Counter
import pickle
import requests
import spacy
from bs4 import BeautifulSoup
import matplotlib.pyplot as plt

!pip list
print('All prereqs installed')

## Verify everything imported correctly, troubleshoot as necessary

## Open Notebook and Complete Tasks
On your machine, open the Jupyter Notebook for editing.
Required: In your Markdown introduction, add a viewable, clickable link to your GitHub repo after your name.
Build your brand and make your Markdown introduction clear and professional.
Required: Use Markdown headings (e.g. Question 1) to clearly show your content by each question number.
Complete the first task.
Execute the notebook. Commit and push to GitHub. Verify your notebook appears correctly.
Complete the second task.
Execute the notebook. Commit and push to GitHub. Verify your notebook appears correctly.
Work this way until all tasks have been completed.
Add packages as needed if you are missing any. 


## Export to HTML and Finalize Repo
Execute each notebook. After executing, export each notebook to HTML. Commit and push your HTML files to your GitHub repo along with the executed notebooks. Verify you have a professional README.md that introduces your GitHub repository and provides helpful information about your project.

## Rubric for grading

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Article text is correct: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Correct scores for first sentence printed: 2 pts (1 / function)
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Histogram shown with appropriate labelling: 1 pt
* (Question 8) Thoughtful answer provided: 1 pt
