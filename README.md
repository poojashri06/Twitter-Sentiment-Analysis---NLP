Twitter Sentiment Analysis - NLP


Dataset Information
The objective of this task is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a racist or sexist sentiment associated with it. So, the task is to classify racist or sexist tweets from other tweets.

Formally, given a training sample of tweets and labels, where label '1' denotes the tweet is racist/sexist and label '0' denotes the tweet is not racist/sexist, your objective is to predict the labels on the test dataset.

For training the models, we provide a labelled dataset of 31,962 tweets. The dataset is provided in the form of a csv file with each line storing a tweet id, its label and the tweet.

Download link: https://datahack.analyticsvidhya.com/contest/practice-problem-twitter-sentiment-analysis/

An end-to-end Natural Language Processing (NLP) pipeline designed to preprocess raw, unstructured Twitter data and classify user sentiments. This project walks through the entire data science lifecycle—from raw text cleaning and vocabulary normalization to feature extraction and machine learning classification.

---

## 🚀 NLP Workflow & Pipeline
The project is executed sequentially within a Jupyter Notebook, containing the following core stages:
* **Text Preprocessing:** Cleaning raw tweets by removing URLs, HTML tags, punctuation, handles, and stop words using the `nltk` library.
* **Exploratory Data Analysis:** Utilizing data visualizations and **Word Clouds** to isolate high-frequency words across distinct sentiment polarities.
* **Feature Engineering:** Converting clean text strings into sparse numerical matrices using **TF-IDF Vectorization**.
* **Model Training & Evaluation:** Training machine learning classifiers (e.g., Logistic Regression) and evaluating performance using Accuracy, Precision, Recall, and **F1-Score**.
* **Threshold Optimization:** Fine-tuning probability classification boundaries (e.g., $P \ge 0.3$) to maximize model utility against class imbalances.

Libraries
pandas
matplotlib
seaborn
scikit-learn
Algorithms
Logistic Regression
Best Model Accuracy: 95.00
