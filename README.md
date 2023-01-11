# Sentiment-Analysis of Tamil tweets (https://archive.ics.uci.edu/ml/datasets/TamilSentiMix)  
This dataset contains tweets in Tamil language with labels as positive,negative, mixed-feelings, not-Tamil and unknwon. The task is to  classify the tweets into these labels. First, the text data (tweets) is preprocessed. Since the tweets are in tamil language , googletranslate API is used to translate tamil tweets to English. Then, NLP based preprocessing steps like removing stopping words, performing stemming and lemmatization are executed. For classification, logistic regression as a classification model is employed. 


