# Sentiment Analysis on Twitter Data

This project performs sentiment analysis on a large dataset of tweets using Python. The dataset contains over 1.6 million labeled tweets, categorized as positive or negative. The main goal is to clean, analyze, and classify tweets based on sentiment using Machine Learning models.

# Features

✅ Load and preprocess the Twitter dataset
✅ Clean tweet text (remove URLs, mentions, hashtags, and special characters)
✅ Perform Exploratory Data Analysis (EDA) to understand sentiment distribution
✅ Convert text into numerical features using TF-IDF Vectorization
✅ Build and evaluate sentiment classification models using Logistic Regression
✅ Measure performance using accuracy, precision, recall, and F1-score

# Tech Stack

Python

Libraries: pandas, numpy, scikit-learn, matplotlib

# Project Structure
📂 sentiment-analysis
 ├── sentiment.ipynb   # Jupyter Notebook with complete code
 ├── train.csv         # Dataset file (1.6M tweets)
 └── README.md         # Project documentation

# How to Run the Project

Clone the repository

git clone https://github.com/your-username/sentiment-analysis.git
cd sentiment-analysis


# Install dependencies

pip install -r requirements.txt


# Run the Jupyter Notebook

jupyter notebook sentiment.ipynb

# Dataset

The dataset used is Sentiment140, which contains 1.6M tweets labeled as:

0 → Negative

4 → Positive

# Results & Insights

Logistic Regression achieved X% accuracy on the test set.

The dataset is balanced between positive and negative sentiments.

Further improvements can include deep learning models like LSTM or BERT.

Future Enhancements

Add more models (Naive Bayes, Random Forest)

Implement word clouds for visual insights

Use neural networks for better accuracy
