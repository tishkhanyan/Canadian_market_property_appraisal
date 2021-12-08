# property_appraisal_project

First I've developed a baseline solution (John's one-step ML algorithm) where I make a data cleanup, some feature engineering and using an ensemble learning with RandomForest, DecisionTree and XGB regressors + Ridge on them I train my algorithm on a train set and test the fitted model on test set. These train/test datasets are generated from 6 files and in total contain ~6000 properties info. 
THe main insight is that as of differences between properties, sold date, etc. the results for predicting house prices using this one-step algorithm is not very high (although 90% of test results lay into <=20% accuracy which is good it is not enough to use this algorithm for correct appraise). 
UPD: There ware three iterations of baseline solution generation where I've played a lot with the data and received huge insights.  

As a next step developed a similarity-based ranking algorithm (say, got the 6 most similar properties to inputted one) and conducted a tricky regression on the prices of these properties generating rather good results using a very "cheap" regressor.

The next step is to develop add the NLP-based analysis part to already developed ones and to see how this additional information will improve the results. Also, some outlier detection, skewness analysis, maybe a better (cleaverer) feature engineering will be done to make this algorithm as usable as it is possible. And, maybe I'll implement more advanced similarity-getting algorithm (although I've already tried different clustering algorithms, however it is possible that I've overseen something).
