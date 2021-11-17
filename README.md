
# Fake-News-Detection
T5o06_FakeNewsDetection
This repo is one of the T5 Bootcamp requirements.


## Abstract

Fake News has become one of the major problems in the existing society. Fake News has high potential to change opinions, facts and can be the most dangerous weapon in influencing society.
This project aimed to uses Machine Learning techniques to classify if the news are fake articles or real articles.

## Design

This project is one of the T5 Data Science BootCamp requirements. Data provided by Kaggle has been used in this project. Classifying news are they real or fake using ML algorithms.

## Data 

The data comes from Kaggle, it is provided in .csv format, you can download it here:

https://www.kaggle.com/sachinsarkar/fake-news-classification-using-naive-bayes/data 

There are two files, one for True\Real news and one for fake news (both in English) with a total of 23481 "fake" articles and 21417 "real" articles.
Each file has 4 attributes, which is:
-	Title: Title of the article, Datatype: object.
-	Text: The text of the article, Datatype: object.
-	Subject: The subject of the article, Datatype: object.
-	Date: The date at which the article was posted, Datatype: object. 

A sample of the True.csv dataset is shown in the following table:


|    | Title | Text  | subject | Date |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| 0  | "As U.S. budget fight looms, Republicans flip their fiscal script"  | "WASHINGTON (Reuters) -The head of a conservative Republican faction in ...” | politicsNews | December 31,2017  | 


A sample of the Fake.csv dataset is shown in the following table:


|    | Title | Text  | subject | Date |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| 0  | “DonaldTrump Sends OutEmbarrassing New Year’s…” | “Donald Trump just couldn t wish all Americans a Happy New Year and leave it at that...” | News | December 31,2017  |  
	

## Tools
* Numpy and Pandas for EDA 
* re for clean data
* seaborn and matplotlib for visuallization 
* sKlearn for modeling
	




