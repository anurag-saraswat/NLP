
# Task_1
- Sentiment Analysis 

# Task_2

## NER_Detection.ipynb
### DataSet : 20Newsgroups dataset
- Run Stanford NER and Spacy NER and extract Named Entities from the data.
- Find the top 100 LOC and PERSON entities from the data set. What is the degree of correlation between the two systems? Consider partial and full matches.

## Custom_NER_Detection.ipynb
### DataSet : 20Newsgroups dataset
- Generate Word2vec, Glove, Fasttext and BERT word vectors for the above corpus.
- Use the NERs detected in previous file to create annotated documents for NER detection. Divide the document collection into training, validation and test data sets. 
Implement a custom NER system (for all 4 vector embedding techniques mentioned in (c)) using LSTM. Compare the results of all models obtained (namely, (i) LSTM with word2vec, (ii) LSTM with glove, (iii) LSTM with fast text,

## Sentiment Analysis Using LSTM
###DataSet : AMAZON review Data Set

Develop an 
- Bi-LSTM based sentiment analysis model using (a) word2vec embeddings (b) glove embeddings.
- BERT based sentiment analysis model. 
- Compare the performance on the test set among these models. (Bi-LSTM (with word2vec, glove), BERT) 
- Also, compare with Traditional ML Models developed in Task_1.



