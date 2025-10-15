# Wine-recommendation-using-text-mining

A Taste of French Wine
In this project, I played with a dataset of wine reviews from Wine Enthusiast(https://www.winemag.com/) website. First of all, I summerized status of French wine in the website. Second, I used the aroma word (Noble et al., 1987, modified) paradigm to calculate the aroma component (word count for each aroma word/total word count of aroma word) of wine from different regions(e.g. Bordeaux: plum: 16.8%, blackberrt: 16.4%; Burgundy: apple 13.2%, plum 12.2%...). This can be applied to recommend consumers wine origin of similar aroma component(using L2 distance). Finally, I compared 2 machine learning techniques, naïve Bayes and k nearest neighbor, to categorize wine description to region of origin.

The dataset is from kaggle(https://www.kaggle.com/zynicide/wine-reviews). There are more than 130 thousand wine reviews in the dataset, with the following columns for each review: country, designation, points, price, province, region_1, region_2, taster_name, taster_twitter_handle, title, variety, winery.
