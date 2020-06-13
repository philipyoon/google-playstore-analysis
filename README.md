# Identifying features that contribute to high install count

When planning to list a mobile application, there is already a list of factors one must consider in order to create a successful app. What kind of app should I make? Does rating or install size even matter to increase the number of users I attract? In this project I identify the features that contribute to a high install count based on [web-scraped data from the Google PlayStore](https://www.kaggle.com/lava18/google-play-store-apps)

I use Altair based on Vega-lite for visualzations and ordered logistic regression from the mord package as the classification model. 5-fold cv leads to a classifier with 63.35% accuracy.

