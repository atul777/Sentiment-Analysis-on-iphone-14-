# Sentiment-Analysis-on-iphone-14-
# PROJECT OVERVIEW

*Problem Statement* : Perform Sentiment analysis to estimate and understand customer 
attitude towards the Apple Iphone14 series

Background:
The Apple iPhone 14 series are smartphones created and manufactured by the Apple Inc. 
The iphone14 represent the 16th generation of iPhones to be launched by apple and were 
announced on September 17th 2022. Some of the major feature improvements to the camera , 
UI display as well as the satellite connectivity.
The production trials were reported to begin in July 2022, with large scale production starting 
in the August. Analysts predicted a strong sales trend despite weak consumer spending due to 
inflation.Apple reported no impact to its production due to geopolitical tensions in the 
August 2022.

Methodology:
Python is the main choice of language used to conduct the analysis. Using queries and 
creation of Twitter API account, tweets were gathered and collected in the form of json files. 
These were fed into different packages in python to conduct and analyze customer perception 
towards iPhone14. 

The following steps were used:-

● Tweepy was used to access Twitter API

● TwitterCollector based on Tweepy wrapper was used to write queries using 
keywords go collect data of interest. These were stored in JSON file.

● JSON files are compatible with Python and the built-in-package JSON which is used 
to work with JSON data.

● Pandas package was used for conducting some of the data analysis. 

● All JSON files were merged into a common JSON file as well as converted to a .csv 
file.

● NLTK package was used for tokenization or splitting of tweets to smaller words. 
This was used to provide an overview of some key parameters such as wordcount, 
use of common stop words etc.

● Wordcloud and matplotlib was used to create word visualization clouds in order to 
visualize and derive some of the frequent words observed in tweets.

● TextBlob was used to understand subjectivity as well as polarity score of these tweets 
to derive insights on customer perception towards iphone14.

Goal:
● The main goal is to understand general market sentiment and polarity towards Apple 
iPhone 14 . This will help gauge if there is a general positive, negative or neutral 
outlook towards the new line of products. 

● Another aim is to calculate the subjectivity score to quantify the amount of personal 
opinions contained in the dataset. The higher subjectivity score means these are 
actually personal opinions of the users and can be a reliable indicator to support the 
polarity score.
