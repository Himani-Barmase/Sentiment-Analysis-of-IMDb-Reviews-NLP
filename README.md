# Sentiment-Analysis-of-IMDb-Reviews-NLP
This Natural Language Processing (NLP) project focuses on analyzing IMDb movie reviews to classify them as positive or negative. The goal is to build a model that can accurately interpret human sentiment from textual data, helping platforms understand audience feedback at scale.
Project Objective
To build a sentiment classification model that processes IMDb reviews and predicts whether a review expresses a positive or negative sentiment. The project emphasizes text preprocessing, feature extraction, and model evaluation for optimal performance.

Data Preprocessing


Performed text cleaning to remove special characters, HTML tags, and numbers.

Applied tokenization to break down text into individual words.

Removed stopwords to eliminate non-informative words.

Used stemming to reduce words to their root forms.

Feature Extraction


TF-IDF (Term Frequency-Inverse Document Frequency): Captured the importance of words in the corpus.

Word2Vec: Represented words as dense vectors capturing semantic meaning.

These techniques transformed raw text into numerical features suitable for machine learning models.

Model Development


Trained multiple classification models including Logistic Regression, Naive Bayes, and Random Forest.

Evaluated models using accuracy, precision, recall, and F1-score.

Fine-tuned models for better generalization and robustness.

Results and Insights


The best-performing model achieved high prediction accuracy on the test set.

TF-IDF performed well with traditional machine learning models, while Word2Vec captured deeper semantic relationships.

The model can effectively classify unseen reviews, making it useful for automated feedback analysis.

Project Structure


Sentiment_Analysis_IMDb.ipynb: Jupyter notebook containing all code and results

data/: Contains IMDb review dataset

visuals/: Includes confusion matrix and performance charts



Tools and Technologies


Python

Pandas, NumPy

NLTK, Scikit-learn

Matplotlib, Seaborn

TF-IDF, Word2Vec

Jupyter Notebook
