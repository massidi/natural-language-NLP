# natural-language-NLP


# Text Preprocessing and Spam Detection

This repository contains Python code for text preprocessing and building a spam detection model using the Naive Bayes algorithm.

## Description

The provided code performs the following tasks:

1. **Importing Libraries**: 
   - `nltk`: Natural Language Toolkit for text processing.
   - `pandas`: Data manipulation library.
   - `re`: Regular expression operations.

2. **Data Preprocessing**:
   - Tokenization of sentences.
   - Removal of non-alphabetic characters.
   - Lowercasing.
   - Lemmatization of words using WordNet.
   - Stopword removal.

3. **Feature Extraction**:
   - **Bag of Words (CountVectorizer)**: Convert text data into numerical features using the count of words.
   - **TF-IDF (TfidfVectorizer)**: Convert text data into numerical features using TF-IDF values.

4. **Model Building**:
   - Splitting the dataset into training and testing sets.
   - Building a Multinomial Naive Bayes classifier.
   - Training the classifier on the training data.
   - Making predictions on the test data.

5. **Evaluation**:
   - Computing the confusion matrix.
   - Calculating the accuracy score.

## Usage

To use this code:

1. Ensure you have the required libraries installed (nltk, pandas, scikit-learn).
2. Download NLTK resources using `nltk.download('all')`.
3. Replace `paragraph` and `messages["label"]` with your own data.
4. Run the script.

## Dependencies

- Python 3.x
- NLTK
- Pandas
- Scikit-learn

## Contributing

Contributions are welcome! Feel free to contribute or provide feedback by opening an issue or pull request.


