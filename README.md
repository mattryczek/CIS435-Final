# Wine Enjoyment Prediction

Yep, just another [wine dataset](https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009) case study. In this iteration, 
my goal was to figure out which wines I would enjoy, with the main variable being `sweetness`. I first attempted to create a regression model,
but this quickly proved counter productive. 

Instead, I chose to demarcate all wines above a certain sweetness as "tasty", remove the variable, and see what a classifier will do with the data.
In this way, I can find other wines I might like, based on the hidden relationships between `residual sugar` and the rest of the features in the set.
