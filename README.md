# Twitter Disaster Prediction

## Overview
This project aims to classify tweets as related to real disaster events or not. The dataset contains over 10,000 tweets labeled as either disaster-related or unrelated. The goal is to build a model that can accurately distinguish between them.

## Dataset
The dataset, sourced from [Crowdflower](https://www.crowdflower.com/data-for-everyone/), consists of tweets containing words like "ablaze," "quarantine," and "pandemonium." Each tweet has been manually labeled to indicate whether it refers to an actual disaster or not.

## Why This Matters
- Helps organizations like emergency response teams and police departments detect real-time disasters from social media.
- Avoids reliance on simple keyword searches, which can lead to false positives (e.g., jokes, movie reviews, or unrelated discussions).

## Data Preprocessing
- Removed unnecessary characters and URLs using regular expressions.
- Converted text to lowercase for uniformity.
- Handled special characters and hashtags while preserving relevant words.

## Model Development
- Used machine learning techniques, including NLP methods, to classify tweets.
- Implemented feature extraction methods such as TF-IDF and Word Embeddings.
- Evaluated model performance using accuracy, precision, recall, and F1-score.

## How to Run the Notebook
1. Clone this repository.
2. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```sh
   jupyter notebook Aryan_twitter_disaster_prediction.ipynb
   ```

## Future Improvements
- Experiment with deep learning models such as LSTMs and Transformers for better accuracy.
- Integrate real-time Twitter API for continuous monitoring of disaster-related tweets.

## Author
Aryan Bhardwaj

Feel free to contribute or reach out with any suggestions!

