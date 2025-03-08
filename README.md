# Spam-classifer-using-NLP
Bag of Words (BoW), Naive Bayes classifier.

![Spam Classifier Screenshot](https://github.com/Torajabu/Spam-classifer-using-NLP/blob/main/Screenshot%202025-03-08%20145902.png?raw=true)


# SMS Spam Detection using Naive Bayes Classifier

This project focuses on detecting spam messages in SMS data using Natural Language Processing (NLP) and a Naive Bayes classifier. The dataset used is the **SMSSpamCollection**, which contains labeled SMS messages as either "ham" (legitimate) or "spam". The project involves:

1. **Data Preprocessing**: Cleaning and preprocessing the text data by removing special characters, converting to lowercase, removing stopwords, and applying stemming.
2. **Feature Extraction**: Creating a Bag of Words (BoW) model using `CountVectorizer`.
3. **Model Training**: Splitting the data into training and testing sets, and training a Multinomial Naive Bayes classifier.
4. **Evaluation**: Predicting spam/ham labels for the test set and evaluating the model's performance.

This project is a great example of applying NLP and machine learning for text classification tasks.

**Technologies Used**:
- Python
- Pandas
- NLTK
- Scikit-learn
