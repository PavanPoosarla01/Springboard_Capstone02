# Sentiment Extraction from Tweets
Author : Pavan Poosarla, Springboard Capstone Project 2

Springboard Data Science Career Track, 2019-20

## Description
The goal of this project is to predict the section of the text which captures the sentiment of the entire text of the tweet. The dataset used for this project is obtained from the Kaggle competition 
https://www.kaggle.com/c/tweet-sentiment-extraction/data

This is completed as Capstone Project 2 for the NLP track of the Springboard data Science career track.

## File Organization
All the files and code are organized into folders. See below for info on each folder
* Notebooks : _Includes all the jupyter notebooks used for coding. The suggeted order is DataWrangling, Storytelling, Statistics, Text Analysis, and Modelling_
* data : _raw, intermin and final data as csv files_
* reports : _Final report and presentation. Also includes interim working documents_

## Conclusion
The project uses both simple and deep learning based approaches to extracting the text that represents the sentiment. The following three approaches are tested
* Bag-of-Words approach : _Use bag of words approach to train a classifier to predict the word in the tweet with the strongest correlation to the sentiment_
* As a QA problem using DistilBERT : _Treat the problem as a question answering problem where the sentiment is the question and selected text in the tweet is the answer. Use a pre-trained DistilBERT model, trained on SQuAD dataset to train on this dataset. 

  

## Author
Pavan Poosarla - Springboard Data Science Career Track, 2019-20

  
 
