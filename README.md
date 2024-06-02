## Toxic Comment Classification Challenge

In this repo, we train and compare the performance of three different models identifying and classifying six types of toxic comments posted online, borrowed from the famous Kaggle dataset from 2018 hosted by Jigsaw/Conversation AI.

# Motivation:

In an era where communication happens across digital platforms at an unprecedented
scale, ensuring a safe and respectful online environment is a pressing concern. The
explosive growth of user-generated content, from social media posts to comments on
discussion forums, brings both tremendous opportunities for interaction and the
challenge of dealing with harmful and toxic content. Content moderation plays a pivotal
role in maintaining the quality and safety of these platforms, and Machine Learning can
help automate this responsibility.

# Overview:

The goal of this project is to build a model that can help in detecting and flagging
content that is (potentially) harmful. This means defining every step of the pipeline:
feature extraction, preprocessing, model building, training, and evaluation.

# About The Dataset

You are provided with a large number of Wikipedia comments which have been labeled by human raters for toxic behavior. The types of toxicity are:

- toxic
- severe_toxic
- obscene
- threat
- insult
- identity_hate

# File descriptions

train.csv - the training set, contains comments with their binary labels
test.csv - the test set, you must predict the toxicity probabilities for these comments. To deter hand labeling, the test set contains some comments which are not included in scoring.
sample_submission.csv - a sample submission file in the correct format
test_labels.csv - labels for the test data

Link to the dataset: https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/

Contributions: Aazen Saleem, Ammar Uppal, Ahmad Xoraiz, Abdulhaseeb Khan

For any further questions/queries, feel free to reach out to me at 25100325@lums.edu.pk
