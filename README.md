# Project Briefing

This notebook intends to build a classification model that categorizes wine reviews according to their grape varieties.
It uses NLTK and a deep neural network to parse the texts. 

The model achieved 72% accuracy in classifying 143,731 reviews to 28 possible varieties.

## Dataset

The dataset consists of wine reviews from the website Wine Enthusiast. The data contains information such as the geographical origin, the variety, and price of each wine. https://www.kaggle.com/zynicide/wine-reviews https://www.kaggle.com/zynicide/wine-reviews/discussion/83970 https://www.kaggle.com/manyregression/updated-wine-enthusiast-review

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
- seaborn
- wordcloud
- os
- keras
- sklearn
- nltk
- imblearn

# Data Preparation and Visualization

Out of 840 wine varieties in the dataset, only 28 contained more then 1,000 reviews and were not a Blend variety.  
The neural network will only use those 28 labels in the dataset, which still account for 81% of the data.


![alt text](https://github.com/fecezar/Capstone/blob/main/cum_freq.png?raw=true)

![alt text](https://github.com/fecezar/Capstone/blob/main/class_imb.png?raw=true)

![alt text](https://github.com/fecezar/Capstone/blob/main/cabernt_wordcloud.png?raw=true)

![alt text](https://github.com/fecezar/Capstone/blob/main/chard_wordcloud.png?raw=true)

![alt text](https://github.com/fecezar/Capstone/blob/main/pinot_wordcloud.png?raw=true)

# Vectorization

a TD-IDF Vectorization was performed on the data and fed into a Neural Network

# Neural Network

Final Accuracy achieved on test data was 72%, considering 28 possible varieties

![alt text](https://github.com/fecezar/Capstone/blob/main/train_acc.png?raw=true)

![alt text](https://github.com/fecezar/Capstone/blob/main/train_loss.png?raw=true)

![alt text](https://github.com/fecezar/Capstone/blob/main/conf_matrix.png?raw=true)
