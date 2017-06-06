# Quora-Question-Pairs

This is my entry for a Kaggle competition designed to detec pairs of duplicate questions asked on Quora. My goal was not
to win the competition---or even to do particularly well---but just to learn some new things. I managed to install and use
the XGBoost package for my classifier, and I learned a little bit about Word2Vec analysis. Most of the things I tried
came from reading the Kaggle message boards about this competition.

I also learned that training a legit model for these types of competitions requries way more computing power
than I have on hand. That's OK as long as I don't want to win. I can do baby versions of the real thing on my laptop,
just as long as the dataset itself has a managable size. For this one, the training and testing data together totaled about
400MB, and that's more-or-less the upper limit of what I can handle locally. Processing this data, even with my simple model,
took several hours of computation.
