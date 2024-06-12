# NBA-MVP-Classification
The goal of this project is to be able to accuracy predict if a given NBA player will be an mvp candidate and if so where will the player rank out of mvp candidates.
In order to do this I will first scrape mvp,player,and team standings data from 1980-2024 using the requests and selenium packages in python.
I will then clean all of the scraped data and merge it into a single dataframe to ensure it is usable for training a machine learning model.
Finally I will train a few different models off of the cleaned data and try to improve models performance if needed.
