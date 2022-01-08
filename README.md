# IMDB_webscraping_analysis
## Project overview
An all encompassing project where I scrape, clean, manipulate and engineer data to create a predictive model that can successfully predict movie IMDB ratings based off of a number of predictor variables. 


The project was split into three main sections:
### 1) Web Scraping 
* Created from scratch a web scraper in R that could:
  * Successfully scrape data from multiple pages and subpages. 
  * Collate the collected data into a tidy dataframe with thousands on records.
* Produced several web scraperers to solve data cleaning problems. 

### 2) Data Cleaning
* Extracted important information from complex strings to create tidy, informative variables using custom made functions.
* Feature engineered new variables to present the data in a more meaningful way.
* Made decisions on how to correctly navigate missing and incorrect data.
* Ensured data integrity was maintained throughout. 
 ![](https://github.com/thickett/IMDB_webscraping_analysis/blob/main/images/cleaning_example_r.PNG)
 
 
 ### Exploratory analysis and feature engineering 
 * Created compelling data vizulizations to outline the scope of the data.
 * Identified key trends and relationships.
 * Feature engineered several new variables  all of which played a pivital role in the success of the predictive model.
 * Normalized the data to ensure distance based, and gradient decent based algorithims performed optimally.
 * Utalised KNN regression to add localised structural information of the data, and to create a new predictor variable.
 
 
 ### Model building and predictions.
 
 * Produced a predictive model that made use of mutliple confounding regression algorithims such as:
  * Elastic net regression.
  * Random forests.
  * XGboost regression trees.
 * Took measures to ensure the predictive model worked well on un-seen data by:
 * Making use of holdout datasets.
 * K-fold cross validation.

