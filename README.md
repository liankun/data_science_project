### Prototyping New store Site selection Model for Beverage Business.


## Meet Fresh Business Background
Meet Fresh is a dessert franchise chain store. The chain specializes in fresh Taiwanese desserts, including  taro balls and grass jelly.  So far, it has 35 stores in the US. Most of them are located in big cities like New York City,  Boston and Los Angeles. The major consumers are Asian, especially from China. Compared with other chain stores like Starbucks,  Meet fresh has great potential in expanding its business.

## Project Background
In order to facilitate the growth of the business, we provide a solution to this: a recommendation system on locations. This system is based on the zip code: each zip code will be given a score measuring the suitability of opening a store. However, Meet Fresh has only 26 stores in the US, which puts a big challenge on building the recommendation system. Given the similarity between the Meet fresh and the bubble tea stores, we generalize the recommendation system to the bubble tea store. In this project, we use the information of  geography,  population,  Big Malls, SuperMarket, Starbucks, McDonald and schools to train our recommendation system by using the techniques including linear regression, random forest, decision tree, neutral network, Xgboost and SVM. We will present the performance of various models and evaluate the best model.  










## Data source and references

shopping mall locations:
https://www.mallsinamerica.com/

demographic data
https://data.census.gov/cedsci/map?q=income&g=0100000US%248600000&tid=ACSST5Y2020.S1901&cid=S1901_C01_001E&vintage=2020&layer=VT_2020_860_00_PY_D1&mode=thematic&loc=38.8800,-98.0000,z8.0000

https://www.kaggle.com/datasets/census/us-population-by-zip-code?select=population_by_zip_2010.csv

https://www.kaggle.com/datasets/jayrav13/unemployment-by-county-us

income data:
https://www.kaggle.com/datasets/pavansanagapati/us-wages-via-zipcode
https://www.census.gov/topics/income-poverty.html

real estate data(rent, debt...)
https://www.goldenoakresearch.com/

yelp reviews:
https://www.yelp.com/dataset

costco locations:
https://www.costco.com/warehouse-locations?langId=-1&storeId=10301&catalogId=10701

starbucks locations:
https://www.kaggle.com/datasets/starbucks/store-locations

school locations:
https://nces.ed.gov/programs/edge/Geographic/SchoolLocations
