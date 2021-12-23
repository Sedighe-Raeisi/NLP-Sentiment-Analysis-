# NLP Sentiment Analysis:
I downloaded the tweets from the following links:   
[**Dataset: www.kaggle.com/kazanova/sentiment140**](www.kaggle.com/kazanova/sentiment140)    
![image](https://user-images.githubusercontent.com/67642255/147139650-867b7348-e6dc-4c82-b122-300d9ae801db.png)  
------
**Preprocessing Text**   
I preprocessed the tweets using nltk packages:
- Cleaning text from unwanted characters
- Cleaning neumerics 
- Removing stop words
- Stemming
- Lemetizing     

**Preprocessing labels**  
Converting categorical baribles to neumerics using Sklearn label encoder.    

# [TfIdf](https://github.com/Sedighe-Raeisi/NLP-Sentiment-Analysis-/blob/main/Tweet_Sentiment_TfIdf.ipynb)
I converted the tweets to TfIdf vectors using Sklearn.   
Then, I used a Random Forest classifier to classify the data.    


![image](https://user-images.githubusercontent.com/67642255/147194977-01a76101-0ee0-4626-9e25-cc9d31679a81.png)   
-----
 **Accuracy = .72**
-----   
# [Embedding](https://github.com/Sedighe-Raeisi/NLP-Sentiment-Analysis-/blob/main/Tweet_Sentiment_Embedding.ipynb)   
I used keras embedding layer. 
Then I added a Conv1D, Maxpooling1D and 2 more dense layer.     


![image](https://user-images.githubusercontent.com/67642255/147195305-6814f3c7-098e-4f26-b511-945906e51cbf.png)   
-----
 **Accuracy = .76**
-----     
# [Glove](https://github.com/Sedighe-Raeisi/NLP-Sentiment-Analysis-/blob/main/Tweet_Sentiment_Prertrained_Glove.ipynb)  
I used glove embedding. 
Then I used two different neural network for classification. Here is the best result emong these two networks:   


![image](https://user-images.githubusercontent.com/67642255/147195416-14a2f968-9293-4663-bcef-989eafe9515e.png)   
-----
 **Accuracy = .77**
-----     
# [Bert](https://github.com/Sedighe-Raeisi/NLP-Sentiment-Analysis-/blob/main/Tweet_Sentiment_BERT.ipynb)  
I used small bert 128 from tensorflow. 
I finetuned it on part of data. 
I add two dens and a classifier layer.    


![image](https://user-images.githubusercontent.com/67642255/147253188-ddfd8c57-f16c-4e4a-abc8-992c0fd8d170.png)
-----
 **Accuracy = .78**
-----


