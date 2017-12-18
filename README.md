# SpookyAuthorID
Data and code for my submission to the 'Spooky Author Identification' Kaggle competition ([Kaggle Competition Home](https://www.kaggle.com/c/spooky-author-identification))

The goal of the competition is to predict which of three authors from a similar genre and era (Edgar Allan Poe, Mary W. Shelley, and H.P. Lovecraft) is the author of a particular sentence.

- The data for the project are in the `train.csv` and `test.csv` files.
- `Spooky-Author-Identification-EDA.ipynb` is a jupyter notebook the contains my EDA for the project.  This includes looking at some differences between the authors' writing styles as well as the creation of word cloud images for each author.
- `Spooky-Author-Identification-Modeling.ipynb` is a jupyter notebook that contains the modeling I have done to try and predict authorship of each sentence in the data.  This includes the creation of classes and functions to generate features and different modeling approaches including Logistic Regression, Random Forest Classification, Neural Net Multiclass Classification, and Multiclass Classification using a Convolutional Neural Network.
