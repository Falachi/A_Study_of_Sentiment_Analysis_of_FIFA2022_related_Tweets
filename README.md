#### Group Members:
- Muhammad Hanif Zulfikri
- Jinan Nisar
- Andy Hadian Shah
- Christopher Liuwell
- Lee Pei Jun
- Ooi Jun Quan

Data is by Tirendaz AI on [Kaggle](https://www.kaggle.com/datasets/tirendazacademy/fifa-world-cup-2022-tweets).

### Abstract
The goal of this project is to execute sentiment analysis on social media (twitter) data consisting of specifically football related tweets. By classifying each tweet in categories of positive, neutral and negative, general sentiment of football fans is gathered and analysed. We have extensively reviewed 10 papers on sentiment analysis on social media data and proposed 3 modifications to meet the sentiment analysis requirements in each step of NLP pipeline. Based on the literature review done, data cleaning methods removal of URLs, emojis, punctuations, stopwords and special characters along with preprocessing methods like contractions expansion, tokenization, lemmatization and stemming was seen to be highly effective. Text representation techniques of TF-IDF and BOW along with external lexicons gave the best results with models like SVM, RF and Linear Regression. This study expects to meet the goals of sentiment analysis with a test accuracy and F1 score of atleast 60% while effectively executing all preprocessing and text representation processes. In total, 9 experiments were run with different preprocessing, text representation and models combinations. Out of these, there were 2 unique experiments for preprocessing to compare stemming and lemmatization, 2 unique experiments for text representation to observe the added effect of Bag-of-bigrams and 3 unique experiments to compare the models of SVM, RF and LR. The combination of Snowball stemming for preprocessing, TF-IDF, BOW, Bag-of-bigrams for text representation and LR for models performed the best with an accuracy of 66% and precision of 69%. We recommend the adoption of this model for NLP tasks of recognizing and classifying sentiment in domain specific social media data, where the data is noisy and contains inconsistencies like emojis, URLs and other non text data.