# TED-Talks-Topic-modeling-and-classification

![alt tag](img.png)

# REPORT:

Business motivation :  Searching TED talks & classifying the based on content. We can extend this and personalize the talks as well. This project is mainly to understand the concepts covered in class and apply them.

Problem formulation :

1- Understanding the topics and words that describe the broad categories of TED talks.

2- classifying the talks based on the content of the talk.

3- Being able to retrieve a relevant TED talk using a sentence or a keyword



## Goal:

#### Topic Modeling 

#### Classify documents into their categories

#### Information retrieval using DOC2VEC

## Data Descreption:

Web scraped TED talk transcripts Category wise

835 TED talks 

5 Categories: 

business = 123 |
entertainment = 152 |
global issues = 245 |
science = 209 |
technology = 249

## Pre-process:

#### encoding

#### Stop words removal and punctuations

#### Lemmatization

#### POS tagging and retaining “NN” and “NNP” -  helps Topic Modeling

## EDA

## Topic Modeling:
TFIDF/count vectorize 

NMF better than LDA

pyLDAvis

Around 45% accuracy after manually labelling the topics and assigning the document to the topic with maximum weight 





# Base line accuracy : 30%

# Accuracy and AUC on TFIDF :

### SVM = ACCURACY: 72% | AUC: 0.88

### Random forest = ACCURACY: 63% | AUC: 0.85

### knn = ACCURACY: 64% | AUC: 0.85

### gradient boosting = ACCURACY: 54% | AUC: 0.74

### LDA = ACCURACY: 49 % | AUC: 0.7 

# Accuracy on Doc2Vec document vectors (Just to see how they perform):

### Random Forest =  ACCURACY: 57%

### Knn = ACCURACY: 56.6%









