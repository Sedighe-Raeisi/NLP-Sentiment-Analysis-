# NLP Sentiment Analysis:
I downloaded the tweets from the following links:   
[**Dataset: www.kaggle.com/kazanova/sentiment140**](www.kaggle.com/kazanova/sentiment140)    
![image](https://user-images.githubusercontent.com/67642255/147139650-867b7348-e6dc-4c82-b122-300d9ae801db.png)

I preprocessed the tweets using nltk packages.   
# TfIdf method
I converted the tweets to TfIdf vectors using Sklearn.   
Then, I used a Random Forest classifier to classify the data.    


# Glove  
I used glove embedding. 
Then I used two different neural network for classification.  
![image](https://user-images.githubusercontent.com/67642255/147139568-2bae71c6-bf11-443a-a8a4-3f9a93c9265c.png)
   
# Bert  
I used small bert 128 from tensorflow. 
I finetuned it on my data. 
I add two dens and a classifier layer. 
![image](https://user-images.githubusercontent.com/67642255/147139508-d35e77c2-039d-4a51-9b99-21df24aa4d0a.png)



