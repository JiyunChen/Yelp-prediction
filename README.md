# Stat-628-Module 2-Yelp Ratings Prediction
Team members: Shiwei Cao, Jiyun Chen, Jing Guo

## Discription
This is a project of STAT628, predicting Yelp ratings based on 1.5 million train data. We use a L2-regularized logistic classfier which spends less than 3 minutes on training a model and yields a RMSE 0.63.

## code
Code for data cleaning and image generating.
 * data_clean_punc.py & data_clean_text.py: data cleanin
 * logit-saga.py: model fitting
 * word cloud plot.R: generating word cloud for categories
 * data_clean_example.py & print_picture.py: jupyter writing
 * word2vec.py: convert words to vectors
 * process_fasttext_result.py: process result of fastText

## data
A link to the raw data and cleaned data.

## image
 * Character Length(star*).png: character length distribution from 1-star to 5-star ratings
 * Negative_Category.png & Positive_Category.png: ratings distribution based on categories
 * Punctuation().png: average ratings vs count of a certain punctuation
 * Wordcloud().png: word tag plots of the most frequent words of four categories.
 * wordcloud.png: overall word importance
 * wordcloud_packages_neg.png & wordcloud_packages_pos.png: word importance with largest negative/positive coefficients

## slides
Two slides used for presentation.

## Yelp_Wed_1.ipynb/pdf
Summary of our whole project.

 
