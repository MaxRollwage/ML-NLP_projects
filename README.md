# ML-NLP_projects

This repository contains an ensemble of different ML and NLP projects that I conducted in my free time. 
These are just examples that I used to learn a few concept and applications of ML techniques

The script "NLP_Twitter_FilterBubble.ipynb" conducts a simple NLP sentiment analysis on tweets from my news feed, compared to all tweets on on twitter. 
If my news feed does not represent the full distribution of sentiments, this could indicate that I am only present with a subset of information, i.e. indicating a "filter bubble". 
As an example I used tweets about Covid-19. 

The script "NLP_Twitter_Stock_dropbox.ipynb" conducts a simple NLP sentiment analysis on tweets from my about dropbox. The idea is whether the sentiment of the tweets represent 
or predict the stock market prize. Hereby, dropbox is just used as an example. 

The script "Predict_Tennis" scrapes data about historic tennis matches to predict future matches. 
Hereby, different classification approaches are compared, with the main idea that consideration of continuous outcome variables (i.e. point difference in the end score)
can be used to improve binary classification (who won the match). Hereby, I compared the same input variables (e.g. world rank of players) to either directly predict the binary 
outcome of the match (using a support-vector classification) or using these input variables for preditcing the the continuous outcome (using a support vector regression) and then further using the prediction of this support vector regression as input to a binary classification of who wins the game. The reason why this two-step process should increase binary classification is that the continuous outcome variable contains more fine grained information for tuning the predictor weights. 
