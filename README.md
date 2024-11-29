# Contextual Analysis of Product Reviews using Text Mining and Clustering

## Project Overview
This project analyzes Amazon product reviews to extract meaningful insights, including:
- Sentiment classification (positive/negative/neutral).
- Keyword analysis.
- Topic modeling with NMF and Latent Dirichlet Allocation (LDA).
- Clustering and visualization using PCA.

## Features
1. Sentiment analysis using `TextBlob` and Transformers.
2. Topic discovery using NMF and LDA.
3. Review clustering with KMeans.
4. Export of labeled datasets (`labeled_reviews.csv`).
5. Visualization of insights via bar charts and scatter plots.

## Requirements
- Python 3.7 or higher.
- Required libraries: `pandas`, `nltk`, `sklearn`, `seaborn`, `matplotlib`, `textblob`.

## Installation
1. Install Python and required libraries: pip install pandas numpy sklearn seaborn matplotlib nltk textblob
2. Download the dataset from Kaggle (`Consumer Reviews of Amazon Products`).
3. Place the dataset in the working directory.

## How to Run
1. Run the script to load and preprocess the data.
2. Perform sentiment analysis to classify reviews.
3. Visualize sentiment distribution, topic discovery, and clustering.
4. Export labeled data as `labeled_reviews.csv`.

## Outputs
- Sentiment Distribution (Bar Chart) along with it's Classification Report(Accuracy)
- Topic Keywords 
- Cluster Visualization (Scatter Plot) along with sihouette score(before and after improving)
- Labeled Dataset (`labeled_reviews.csv`)

## Troubleshooting
- Ensure the required libraries are installed.

## Contact
**Email**: saisowmya.bandaluppi@gwu.edu 

