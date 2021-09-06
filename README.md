# Social_studies_lab 

INTRODUCTION
------------

 * This file consist of short and structured comments for jupyter notebook used in Social Science lab SoSe21:
 * Topic:
    Preferences between NA and EU games in board games.
------------

1. BGG Forum data overview.ipynb 
   - notebook to analyse avaliable data set from BGG (https://boardgamegeek.com/thread/2287371/boardgamegeek-games-and-ratings-datasets)


SCRAPING
------------
2. Scrape initial list of games to work with.ipynb 
   - notebook with code to scrape top games (name, id, url)

3. Assestment of how many pages to scrape.ipynb 
   - notebook with code to understand how many pages we can scrape considering average time to scrapte 1 page (~13 seconds) and necessary number of rating needed to answer research question

4. Scrape games categories.ipynb 
   - notebook with code to scrape list of categories of each game (i.e Fantasy, CardGame, Wargame, Medieval and so on)

5. Scrape. Num of pages from games.ipynb 
   - notebook with code to scrape number of ranting pages of each game.
     Number of pages we need to randomly choose 20 pages on next steps

6. Scrape game additional data (playing time, age, num of players).ipynb
   - notebook with code to scrape playing time, age, num of players of 1000 games

7. Main scraper. Scrape rating with random pages.ipynb
   - notebook with code to scrape 1000 ratings info of each game


DATA READING, PRELIMINARY ANALYSIS & TRANSFORMATION
-----------------------------
8. Folders reading for scraped files and short analysis.ipynb
   - notebook with code to form one dataset of all scraped ratings and short analysis of data

9. Categories transformation.ipynb
   - notebook with code to make game cateroies trasformation from list to binary columns 

10. Preliminar analysis of descriptive games attributes.ipynb
   - notebook with code for preliminary analysis of descriptive games attributes (playing time, age, num of players)


ANALYSIS
---------
11. Descriptive stat.ipynb
   - notebook with code to calculate Descriptive stat

12. Answering reserach question (subquestions 1-2).ipynb
   - notebook with code to answer subquestion 1 (Hypothesis test and efect size calculation), subquestion 2 (p-value and effect size calculation for top 20 catregories for 2 continents)

13. Regression BGG (subquestions 3).ipynb
   - this notebook is expansion of Bhanu.Vijayaraj's analysis notebook with code of RandomForestRegressor and LinearRegression to answer subquestions 3 (which features play main role in average rating prediction). 

14. Popularity_of_categories (research subquestion 4).ipynb
   - notebook with code to answer research subquestion 4

15. rating_chi_test.ipynb 
   -  Are ratings and continents dependent on each other ? (research subquestion 5)
















