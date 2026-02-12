# sentiment-analysis-of-a-movie-review


Project Overview
This project builds a machine learning model to classify movie reviews as positive or negative using natural language processing techniques. The model is trained on the IMDB Large Movie Review Dataset and performs text preprocessing, feature extraction, and supervised classification using Scikit-learn.

The goal of this project is to analyze sentiment distribution and extract meaningful insights from large scale unstructured text data.

Dataset
The dataset used is the IMDB Large Movie Review Dataset containing 50,000 movie reviews.
25,000 reviews are used for training and 25,000 for testing.
The dataset is balanced with equal positive and negative samples.

The dataset is not included in this repository due to size constraints.
You can download it from:
https://ai.stanford.edu/~amaas/data/sentiment/

After downloading, extract the dataset and place it inside the project directory.

Technologies Used
Python
Pandas
NumPy
NLTK
Scikit-learn
Matplotlib
Seaborn

Project Workflow

Data Preprocessing
Removed HTML tags
Converted text to lowercase
Removed punctuation and special characters
Removed stopwords
Tokenized text

Feature Engineering
Used Bag of Words representation
Used TF-IDF vectorization to convert text into numerical features

Model Building
Trained classification models including Logistic Regression and Naive Bayes

Model Evaluation
Evaluated performance using accuracy score, confusion matrix, precision, recall, and F1-score

Results
The final model achieved 91.44 percent accuracy on the test dataset.
The model successfully classifies unseen reviews and demonstrates strong generalization performance.
