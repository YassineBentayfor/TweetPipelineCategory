# TweetPipelineCategory

DeepTweets: Classifying Sports and Politics Tweets

This project uses machine learning techniques to classify tweets as either related to sports or politics. The dataset used for this project consists of tweets collected from Twitter's API, and was preprocessed to remove stop words and unwanted characters. The resulting text was then vectorized using a CountVectorizer, and four different machine learning models (Multinomial Naive Bayes, Logistic Regression, Random Forest, and Support Vector Machine) were trained to classify the tweets.

The performance of each model was evaluated using confusion matrices, which were plotted using ConfusionMatrixDisplay. The models were also evaluated using metrics such as accuracy, precision, recall, and F1 score.

This project was implemented using Python, and makes use of several libraries such as pandas, scikit-learn, nltk, and matplotlib. The code is available in the Jupyter notebook deeptweets.ipynb.

To run the code, you will need to install the required libraries by running pip install -r requirements.txt. You will also need to provide your own Twitter API credentials to collect additional data, or modify the existing dataset to suit your needs.

Feel free to use this project as a starting point for your own Twitter classification tasks, and don't hesitate to contribute improvements or bug fixes!
