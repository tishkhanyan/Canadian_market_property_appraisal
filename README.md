# property_appraisal_project

First I've developed a baseline solution that was using a small part of data which wasn't requiring a cleanup. 
Then I've made some feature engineering and data cleaning such that very simple algorithms like linear regressor and random forest are able to train at that. 
This I've called a baseline solution. 

As a next step developed a similarity-based ranking algorithm (say, got the 6 most similar properties to inputted one) and conducted a tricky regression on the prices of these properties generating rather good results using a very "cheap" regressor.

The next step is to develop add the NLP-based analysis part to already developed ones and to see how this additional information will improve the results. Also, some outlier detection, skewness analysis, maybe a better (cleaverer) feature engineering will be done to make this algorithm as usable as it is possible. And, maybe I'll implement more advanced similarity-getting algorithm (although I've already tried different clustering algorithms, however it is possible that I've overseen something).
