# Yelp\_reviews\_Text\_Analytics

## Overview

This repository contains NLP analysis on Yelp reviews, using various text processing, visualization, and sentiment analysis techniques. The project is divided into two main notebooks:

1. **Lift Analysis, MDS, Stemming, and Lemmatization**
2. **Sentiment Classification, Cosine Similarity, and VADER Analysis**

Each notebook addresses different aspects of NLP, from text normalization to sentiment prediction and similarity measures.

## Notebook 1: Lift Analysis, MDS, Stemming, and Lemmatization

### Techniques Used:

- **Word Frequency & Word Cloud Generation**
  - Tokenization and stopword removal
  - Word count analysis and visualization
- **Lift Matrix Calculation & Visualization**
  - Computes co-occurrence relationships between words
  - Uses **Multi-Dimensional Scaling (MDS)** to create better visual representation
- **Text Normalization**
  - **Stemming** using Porter Stemmer
  - **Lemmatization** using WordNet Lemmatizer

## Notebook 2: Sentiment Classification, Cosine Similarity, and VADER Analysis

### Techniques Used:

- **Sentiment Classification**
  - Converts numerical ratings into binary sentiment labels
  - Uses **VADER** sentiment analysis to classify review polarity
- **Cosine Similarity for Text Comparison**
  - Uses **TF-IDF vectorization** to convert text into numerical format
  - Computes **cosine similarity** to measure textual closeness between reviews

## Data

The dataset contains **460 Yelp reviews** with the following columns:

- **Reviewer**: Name of the reviewer
- **Rating**: Integer rating (1-5 scale)
- **Review**: The actual text of the review

## Libraries Used

- **NLTK** (Tokenization, Stopwords, Stemming, Lemmatization)
- **Scikit-learn** (TF-IDF Vectorization, Cosine Similarity, MDS)
- **VADER** (Sentiment Analysis)
- **WordCloud** (Visualization)
- **Matplotlib & Seaborn** (Plotting and Visualization)
- **Pandas** (Data Handling)

## How to Run

1. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the Jupyter Notebooks in the following order:
   - `Lift_MDS_Stemming_Lemmatizing.ipynb`
   - `Sentiment_Classifier_Cosine_similarity_VADER.ipynb`
3. Modify and analyze the results as needed!

---

Feel free to contribute or suggest improvements!

