## In progress...


##  Introduction 
This repository contains several chess related web scraping projects. My goals were to practice using webscraping tools like pandas.read_html, BeautifulSoup, and Selenium to extract and analyze data from chess websites.

Chess player performance is measured using an Elo rating system where wins, draws, and losses cause ratings to fluctuate. Using this rating information, chess federations like the world chess federation (FIDE) and the United States Chess Federation (USCF) publish public monthly player lists. In addition to ratings, federations also publish player attributes like sex, country, date of birth, etc. This makes chess websites a rich source for data science related projects. 

What makes the data produced in these projects different from other sources is the fact that all of the chess players monthly ratings are available in a single data set. Normally, one would have to combine a bunch of these monthly data sets in order to get a complete picture of chess player rating tajectories. This project eliminates that problem by providing all of FIDE provided monthly rating supplements together in one data set. 

## Projects
 
### [Project 1: "Elite Chess Grandmaster Web Scraping Project" (chess_project.ipynb)](https://github.com/larylc/Chess-Webscraping-Projects/blob/main/chess_project.ipynb)
**Summary**: Produced csv file of top 100 FIDE rated chess players and their rating histories using webscraping tools. 

<details> 
<summary><b>See Libaries Used:</b></summary>
  
* pandas
* Selenium
* requests
* Beautiful Soup
* pprint

</details>

### [Access File](https://github.com/larylc/Chess-Webscraping-Projects/blob/main/top_grandmasters.csv)
---

### [Project 2: "The Path to Chess Masterhood Part 1" (chess_project_masters.ipynb)](https://github.com/larylc/Chess-Webscraping-Projects/blob/main/chess_project_masters.ipynb)

**Summary**: Produced csv file of all FIDE rated chess players above 2200 and their rating histories up to June 2021.

<details>
<summary><b>See Libaries Used:</b></summary>
 
* pandas
* requests
* Beautiful Soup
* pprint

</details>

### Access File: The csv for this project is too large.
---

## CSV Files

The web-scraping projects produced data sets up to June 2021. Using the same procedures as above, more recent September data was produced. Unfortunately, some of the files were too large to upload on GitHub, so the ones that were small enough were uploaded. 





## Contact Me

|**Contact Method**  |                          |
| -------------------| -------------------------|
| Professional Email | cedric.lary1@gmail.com   |




