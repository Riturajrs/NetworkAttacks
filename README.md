# NetworkAttacks

# Link to contest:
https://www.kaggle.com/competitions/network-attacks-prediction

# Approach:
I used Random Forest Classifier for this problem. I imported it from sklearn and trained it with test-train split of 0.8. The predictions which were in the form of text, had to be mapped to numbers for training and prediction. I used 1000 trees for estimation and assigned bootstrap to false, so that the trees were not pre-trained. Given the number of features, in my knowledge, Random Forest Classifier was the best approach.