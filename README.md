
# Stance-detection-on-cryptocurrency-using-twitter-data

Stance classification in tweets on ethereum using deep neural networks

Stance classification is a subcategory of opinion mining where the task is to automatically determine whether the author
of a piece of text is in favor or against a given target. It can be formulated in different ways. In our context, we define
stance detection to mean automatically determining from the text whether the author is in favor or against of the given
target, or whether neither inference is likely.

In this project, a Deep Learning technique is used to automatically detect the stance of a
particular tweet, when the tweet statement and target of that tweet is provided. The data related to ethereum was scraped from twitter and necessary training was performed


Files included for this task are listed below:

1> twitter_ethereum_annotated_stance_train.csv : CSV containing annotated tweets used for training the models

2> twitter_ethereum_annotated_stance_test.csv: CSV containing annotated tweets used for evaluating the models

3> glove.twitter.27B.100d.txt : pertained GloVe word vectors 

4> ethereum_stance_detection.ipynb : Code file containing the models, configurations and results. The file includes all the comments and instructions required



# Sentiment-analysis-on-cryptocurrency-using-twitter-data

Sentiment Analysis in tweets on ethereum using classifiers and Pre-trained models

Sentiment analysis is a task of finding true sentiment in a tweet irrespective of any target

For this task text based classifiers and pre trained models from hugging face with and without fine tuning have been used

Files included for this task are listed below:

1> twitter_ethereum_annotated_all.csv : CSV containing entire dataset consisting of 2755 tweets which were manually annotated

2> ethereum_twitter_sentiment_analysis.ipynb: Code file containing the models and results. The file includes all the comments and instructions required

3> RobertaForSequenceClassification8.model : Model saved at EPOCH 8 after fine tuning 


#Other files:

1> ethereum_data_collection.ipynb —> Code file used for collecting top 100 crypto influencers and tweets on ethereum by these influencers 
