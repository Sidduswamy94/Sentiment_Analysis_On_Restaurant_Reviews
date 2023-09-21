# Sentiment_Analysis_On_Restaurant_Reviews

The objective of this project is to develop a predictive model for restaurant reviews, classifying them as positive or negative using machine learning. The data was sourced from Kaggle and underwent a comprehensive data cleaning process, which included tasks such as tokenization, lemmatization, punctuation removal, eliminating stopwords, special characters, digits, URLs, and emoji’s. The dataset was then split into training and testing sets, and a model pipeline was created.

The pipeline consists of:

•	CountVectorizer to convert the text data into a numerical format.

•	TfidfTransformer to assess the importance of words in a document.

•	Training Respective Model's.

We employed several predictive algorithms, including Multinomial Naive Bayes, XGBoost (XGBClassifier), LightGBM (LGBMClassifier), K-Nearest Neighbors (KNNClassifier), Random Forest (RF), Logistic Regression (LR), and Support Vector Machine (SVM). Subsequently, we performed predictions and evaluated the performance of each machine learning algorithm.

After comparing the results, we found that the Logistic Regression (LR) algorithm demonstrated the highest test accuracy and cross-validation score. Specifically, the Logistic Regression model achieved a test accuracy of 78% and a cross-validation score of 79%. As a result, based on these performance metrics, we have selected Logistic Regression as the best-performing model for our task.
