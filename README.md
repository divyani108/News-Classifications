# News-Classifications
Objective
This project aims to build a model that classifies whether a given news article is genuine or fake using Natural Language Processing (NLP) techniques. It utilizes the Fake.csv and True.csv datasets for training and testing. The primary goal is to employ supervised learning algorithms to accurately classify news articles based on their authenticity.
Concepts Involved
Supervised Learning: The project utilizes supervised learning techniques, where the model learns from labeled examples (i.e., news articles labeled as genuine or fake) to make predictions on new, unseen data.

Text Pre-processing: Before training the model, the text data undergoes pre-processing steps such as tokenization, stop-word removal, and stemming to clean and standardize the text, making it suitable for analysis.

Vectorization: The text data is transformed into numerical vectors using techniques like TF-IDF (Term Frequency-Inverse Document Frequency) or Bag-of-Words, enabling machine learning algorithms to process the data.

Scikit-Learn NLP Imports: The project leverages various modules and functionalities from the Scikit-Learn library for NLP tasks, including text processing, feature extraction, and model training.

Natural Language Toolkit (NLTK): NLTK is utilized for additional text processing tasks such as tokenization, stemming, and part-of-speech tagging, enhancing the quality of the textual data for classification.

ML Classifiers: Several machine learning classifiers are employed for training and evaluating the model's performance, including but not limited to:

Support Vector Machines (SVM)
Naive Bayes
Random Forest
Gradient Boosting
