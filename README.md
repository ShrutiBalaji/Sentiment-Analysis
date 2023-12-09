# Sentiment-Analysis
Task: Webscrap
The Binary sentiment classification file does not contain a machine learning model but just the webscrapping using python to make the prediction using a normal python library. 
Whereas the Sentiment Analysis file follows the thorough steps in the process of Natural Language processing starting from data evaluation, data preprocesing, vectorization, model creation, model evaluation. 

Preprocessing done:
1. Removing duplicates
2. Transformed text to lower case
3. Dropping missing values
4. Tokenize the sentences to words
5. Remove stop words
6. Stemming tokens into root forms

Feature Engineering
1. SMOTE for oversampling positive dataset
2. TFIDF for vectorization of words into matrices
3. One hot encoding

Model Used
1. XGBoost
2. Gradient Boosting Classifier
3. MultinomialNB
4. Neural Networks
5. Support Vector Machine (SVM)
