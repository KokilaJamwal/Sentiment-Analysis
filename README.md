## Sentiment-Analysis of Tamil tweets (https://archive.ics.uci.edu/ml/datasets/TamilSentiMix)  
This dataset contains tweets in Tamil language with labels as Positive,Negative, Mixed-feelings, not-Tamil and unknwon_state. We removed the class labels which were not of our interest like not_Tamil and unknown_state. The task is to  classify the tweets into these labels. Since the tweets are in tamil language, googletranslate API is used to translate tamil tweets to English. Then, NLP based preprocessing steps like removing stopping words, performing stemming and lemmatization are executed. For classification, logistic regression as a classification model is employed. As a metric, F1-score is used to evaluate the performance of the model. 


