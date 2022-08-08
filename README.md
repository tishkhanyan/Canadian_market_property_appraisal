# property_appraisal_project

This was a real ML project on Canadian property appraisal. The project was more about research and the main question was if the descriptions of properties given to computer will improve the house price prediction accuracy. 

First step: data cleanup, outlier detection, skewness analysis, some feature engineering.

Second step: ensemble learning with RandomForest, DecisionTree and XGB regressors + Ridge on train/test datasets are generated from ~6000 datalines for Canadian property dataset. Main insight here: as of the data type (seems that in Canada the house appraisal project is super subjective) such algorithm are not giving good results (although 90% of test results lay into <=20% accuracy it is not enough to use this algorithm for correct appraise). 

Third step: a L1-similarity-based ranking algorithm (say, using the 6 most similar properties to the inputted one) and conducted a tricky regression on the parameters of these properties generating rather good results using a very "cheap" regressor. 

Final step: adding NLP - taking into account the text descriptions of the properties. In fact the algorithm accuracy improvement gain is so small that seems that the descriptions are giving not so important information. And this was the main question of the project - is it possible to improve the appraisal quality using additional data from the descriptions of the properties IN AN AUTOMATED WAY (i.e. different NLP algorithms).


*** Files containing the data are not for sharing.
