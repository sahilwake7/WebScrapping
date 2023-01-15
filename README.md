
# Web Scrapping Project

Web scraping is the process of extracting and parsing data from websites in an automated fashion using a computer program. It's a useful technique for creating datasets for research and learning.


## What you will learn from this post:
* basic understanding of web scraping
* how to extract data from a website using classes and HTML tags
* how to use requests module to get data
* how to use Beautifulsoup
## Steps to follow
1) We're going to scrape https://github.com/topics.

2) We'll get a list of topics. For each topic, we'll get topic title, topic page URL and topic description

3) For each topic, we'll get the top 25 repositories in the topic from the topic page

4) For each repository, we'll grab the repo name, username, stars and repo URL

5) For each topic we'll create a CSV file in the following format:
Repo Name,Username,Stars,Repo URL
## Requirements
* bs4
* requests
* python3
## How to run this code
* one can run Scraping with WebScrappingFinal.ipynb file in jupyter notebook /li>
* one can install juypyter notebook by this command "pip3 install jupyter"