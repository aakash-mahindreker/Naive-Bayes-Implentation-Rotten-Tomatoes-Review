# Naive-Bayes-Implentation-Rotten-Tomatoes-Review
UTA CSE 5334: Data Mining - Text Classifier Assignment

The .ipynb file is the Naive Bayes implementation using the rt_reviews.csv dataset (https://www.kaggle.com/datasets/ulrikthygepedersen/rotten-tomatoes-reviews) for text classification. There are two classes in the dataset which are represented as Freshness for the Review. The values of Freshness are either "fresh" or "rotten". In this assignment we assume "fresh" and "rotten" as the representations for "Positive review" and "Negative review" respectively. 

Procedure for the implementation is as follows:
1. Load and split the dataset into Train data, Development data and Test data.
2. Buid a vocabulary list and store their count values.
3. Using the vocabulary list, calculate the probailities of word occuring in the dataset, probability of word occuring in the Positive review (reviews with Freshness: "fresh") and the probability of word occuring in the Negative review (reviews with Freshness: "rotten").
4. Using the calculated probabilities and thr conditional probabilities, build a prediction model that predicts takes reviews and predicts the class of the review. 
5. Calculate the accuracy using Development data/ Validation data. 
6. Experiment the smoothing and word filtering to improve the accuracy.
6. Using the test data find the final accuracy of the prediction method.

To understand the procedure, I have posted a blog on my website which will guide you for developing your own Naive Bayes classifier. Also, I have provided the source code along with the references which will help in improving the accuracy. 
Follow the link to blog: https://aakashmahindreker.wixsite.com/aakashmahindreker/post/naive-bayes-implementation-text-classification

Note: This is just a simple Naive Bayes Implementation and it does not focus more on improvement of accuracy. However, it gives a better idea to the reader, on how the accuracy can be improved.

Author: Aakash Mahindreker
UTA ID: 1002027304
Date of Submission: 16 April, 2023.
