## AA_Classification_Modelling_Project

## Description / Business understanding:

I was given a dataset (bbc-text.csv) consists of 2225 documents from the BBC news website corresponding to stories in five topical areas from 2004-2005.  <br>
The csv file consists of two columns, first being the “category”, which are the labels for each document: business, entertainment, politics, sport, and tech. Second column is “text”, which is the BBC news stories/ Document.  <br>

The goal to preprocess and transform the data into either bag-of-words or TF-IDF matrix, then fit the data into various classification models to classify the BBC news stories into different categories and lastly, comparing the performance of each model.  <br>


## Data Understanding and pre-processing
The first step will be text data pre-processing. Started off by extracting the data from the csv file and store it inside a data frame, followed by data cleansing using proper techniques such as removing stop words, stemming and lemmatizing.  <br>
<br>
![image](https://user-images.githubusercontent.com/73086331/144260531-a443c8a6-44b1-47e5-a249-db1442ebf194.png)
^ It has a two columns, first being the category column, which indicates which category that the text column belongs to
 <br>
![image](https://user-images.githubusercontent.com/73086331/144260436-cbdb1dbc-7aee-432d-9c01-93afa401f902.png)
^Before cleansing
<br>
![image](https://user-images.githubusercontent.com/73086331/144260788-1de3e656-f2ba-4849-8a1f-7fb6155049bb.png)
^After cleansing

## Data Tranformation
And lastly, the cleansed text data will be transformed into bag of words or TF-IDF matrix for classification modelling later.  <br>
For step 2, it will be text data understanding, first by extracting the keywords from each document using TF-IDF matrix, the keywords extracted can be then used for analysis using Association Rule Mining.  <br>

The goal is to visualize and understand the associations between the keywords by category or by overall documents.   <br>

## Modelling (Classification model)
For step 3, it aims to use classification modellings on bag-of-word or TF-IDF matrix to classify the BBC news stories into different categories.  <br>

## Model Evaluation
And to evaluate the models performance using testing data and further improve the model performance by tuning model hyperparameters or further cleanse or transform the text data. The last step is to summarize the findings, which can be a collection of accuracy scores from different models using either bag-of-word or TF-IDF matrix and choose the most suitable model to use to classify future data. And finally, some possible improvements to be made. <br>

 

