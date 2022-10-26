# sentiment-analysis-on-Amazon-product-reviews-using-Machine-and-Deep-Learning-models
"Sentiment Analysis and Classification Project using Amazon dataset and using ML and DL models."
Here, I am specifically mentioning that you have to install the pandas_profiling from colab only because its not working in Jupyter.
you have to run this code snippet in colab,

!pip install -U pandas-profiling --user
!pip install https://github.com/pandas-profiling/pandas-profiling/archive/master.zip
import pandas_profiling
from pandas_profiling.report.presentation.flavours.html.templates import create_html_assets

I have downloaded the dataset- "womens clothing E-commerce reviews" and did the EDA, visualization part. Then I tried to find the target class variable, its proportion, alos checked other features. After checking the frequecy of top 200 words i have finally selected the feature and did the data cleaning. Now, comes the important part- "Text Mining", here I tried several methods like finding the stopwords, removing punctuations, lemmatizing, handling rare words. I have made the wordcloud of repetative words, negative words, positive words. After doing all this finally I started with the ML & DL part. After applying CountVectorizer I splitted the dataset, applied ML models like Logistic Regression, SVM, Random Forest, Ada Boosting and applied DL models like GRU while using ADAM optimizer and early stopping. Plotted the evaluation and predicted outcomes. Lasltly I have done the comparison.


I have done the above course project during my course-work "Advanced Programming in Python(DSE309)" while studying at Indian Institute of Science Educatioon and Research(IISER) Bhopal in the 3rd year of my BS.
