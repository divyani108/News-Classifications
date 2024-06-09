# News-Classifications
## Objective

This project aims to build a model that classifies whether a given news article is genuine or fake using Natural Language Processing (NLP) techniques. It utilizes the `Fake.csv` and `True.csv` datasets for training and testing. The primary goal is to employ supervised learning algorithms to accurately classify news articles based on their authenticity.
## Concepts Involved

- **Supervised Learning:** The project utilizes supervised learning techniques, where the model learns from labeled examples (i.e., news articles labeled as genuine or fake) to make predictions on new, unseen data.
  
- **Text Pre-processing:** Before training the model, the text data undergoes pre-processing steps such as tokenization, stop-word removal, and stemming to clean and standardize the text, making it suitable for analysis.
  
- **Vectorization:** The text data is transformed into numerical vectors using techniques like TF-IDF (Term Frequency-Inverse Document Frequency) or Bag-of-Words, enabling machine learning algorithms to process the data.
  
- **Scikit-Learn NLP Imports:** The project leverages various modules and functionalities from the Scikit-Learn library for NLP tasks, including text processing, feature extraction, and model training.
  
- **Natural Language Toolkit (NLTK):** NLTK is utilized for additional text processing tasks such as tokenization, stemming, and part-of-speech tagging, enhancing the quality of the textual data for classification.
  
- **ML Classifiers:** Several machine learning classifiers are employed for training and evaluating the model's performance, including but not limited to:
  - Support Vector Machines (SVM)
  - Naive Bayes
  - Random Forest
  - Gradient Boosting

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/news-authenticity-classifier.git
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Download the `Fake.csv` and `True.csv` datasets and place them in the `data/` directory.

4. Run the application:
   ```
   python main.py
   ```

## Usage

After installing and running the application, you can:

- Train different classifiers with the provided datasets.
- Evaluate the performance of each classifier using metrics such as accuracy, precision, recall, and F1-score.
- Classify new news articles using the trained models.

## Dataset

This project utilizes the `Fake.csv` and `True.csv` datasets. These datasets contain news articles labeled as genuine or fake. You can download the datasets from [source] or use your own datasets for experimentation.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:
- Fork the repository.
- Create a new branch (`git checkout -b feature/your-feature`).
- Commit your changes (`git commit -am 'Add new feature'`).
- Push to the branch (`git push origin feature/your-feature`).
- Create a new pull request.

## Usage

You can look for detailed explanation with graphs at - news.ipynb
You can also run the python file using -  python3 news.py

## Contact

For questions or suggestions regarding this project, please contact [Divyani Singh] at [divyanisingh108@gmail.com].
