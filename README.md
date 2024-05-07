# NLP Sentiment Analysis on Amazon Consumer Reviews Dataset

## Overview

This project focuses on sentiment analysis using Natural Language Processing (NLP) techniques on the **Datafiniti_Amazon_Consumer_Reviews_of_Amazon_Products_May19 dataset** sourced from Kaggle. The goal is to determine the sentiment (positive, neutral, or negative) of Amazon product reviews using two different NLP libraries: **Spacy with TextBlob and NLTK with VADER**.


**Dataset**

Due to the large size of the dataset, it cannot be uploaded to GitHub. You can download the dataset from Kaggle.

**Libraries Used**

NumPy

Matplotlib

Pandas

Spacy

TextBlob

WordCloud

NLTK

SentimentIntensityAnalyzer (VADER)

ConfusionMatrixDisplay (Scikit-learn)


## Project Structure

Importing Libraries: Necessary libraries are imported.

Mounting Dataset: Mounting the dataset from Google Drive.

Exploratory Data Analysis (EDA): Understanding dataset shape, columns, and data types.

Data Cleaning: Checking for missing values, empty cells, and whitespace cells.

NLP Model Creation: Using Spacy and TextBlob for polarity analysis.

Evaluation: Comparing polarity analysis results with review ratings.

Visualization: Generating word clouds for positive, neutral, and negative words.

NLTK Sentiment Analysis: Using NLTK with VADER for sentiment analysis.

Conclusion: Discussing strengths, limitations, and overall performance of both models.

**How to Use**

Download the dataset from the provided Kaggle link.

Upload the dataset to your Google Drive or local environment.

Run the provided code in your preferred environment (e.g., Google Colab, Jupyter Notebook).

Follow the code comments and outputs to understand the analysis process.

Analyze the generated confusion matrices and accuracy scores for model evaluation.

**Important Notes**

The dataset used is for Amazon consumer reviews, focusing on product ratings and review texts.
Due to the nature of sentiment analysis, results may vary based on dataset characteristics and NLP library used.
Consider using different NLP models or adjusting parameters for improved accuracy based on specific project needs.
Feel free to modify and expand upon this project as needed for your analysis and learning objectives.
