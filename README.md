# News Sentiment Analysis

## Overview
This project performs sentiment analysis on news articles to classify them into Negative, Neutral, and Positive categories using Logistic Regression.

## Dataset
The dataset used is a collection of news articles, which is included in the `data` folder.

## Methodology
1. **Data Preprocessing**: Cleaned the text data, removed punctuation, numbers, and extra whitespace.
2. **Feature Extraction**: Transformed text data into numerical features using TF-IDF Vectorization.
3. **Model Training**: Applied Logistic Regression to classify sentiments.
4. **Evaluation**: Assessed model performance using accuracy, classification report, and confusion matrix.

## Instructions
1. **Run the Code**: Execute `src/news_sentiment_analysis_and_prediction.py` to train the model and view the evaluation metrics.
2. **Data File**: Dataset is placed in the `data` folder.

## Results
The model provides sentiment classification accuracy along with a detailed classification report and confusion matrix.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
