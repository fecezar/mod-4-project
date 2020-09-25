# Project Briefing

## Dataset

The dataset consists of wine reviews from the website Wine Enthusiast. The data contains information such as the geographical origin, the variety, and price of each wine. https://www.kaggle.com/zynicide/wine-reviews

 ## Objective

The objective is to see how well a Neural Network can predict the wine variety from the description provided by the reviewers.

# EDA

## Libraries

- pandas
- numpy
- string
- re
- wordcloud
- tensorflow
- pickle
- matplotlib
- os
- keras
- sklearn
- nltk


# Data Preparation and Visualization

Out of the over 700 wine varieties in the dataset, only 99 contained more then 100 review. 
The neural network will only use those 99 labels in the dataset


https://github.com/fecezar/mod-4-project/blob/master/1.png

https://github.com/fecezar/mod-4-project/blob/master/2.png

https://github.com/fecezar/mod-4-project/blob/master/3.png

https://github.com/fecezar/mod-4-project/blob/master/4.png

https://github.com/fecezar/mod-4-project/blob/master/5.png

# Vectorization

a TD-IDF Vectorization was performed on the data and fed into a Neural Network

# Neural Network

Final Accuracy achieved on test data was 61%, considering 99 possible labels

https://github.com/fecezar/mod-4-project/blob/master/6.png
