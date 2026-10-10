# Sentiment Analysis using Machine Learning

## Project Overview
This project uses Machine Learning to classify customer reviews as **Positive** or **Negative** sentiments.

## Dataset
- Total reviews: 2,748
- Amazon reviews: 1,000
- Yelp reviews: 1,000
- IMDb reviews: 748

## Technologies Used
- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression
- Google Colab

## Project Workflow
1. Load and explore the dataset.
2. Prepare review text and sentiment labels.
3. Split data into training and testing sets (80/20).
4. Convert text into numerical features using TF-IDF.
5. Train a Logistic Regression model.
6. Evaluate the model using accuracy, precision, recall, F1-score, and a confusion matrix.
7. Predict sentiment for new reviews.

## Model Performance
- **Test accuracy: 81.64%**
- Training samples: 2,198
- Testing samples: 550

## Sample Predictions
- "The product is amazing and very useful" — Positive
- "The product is very bad and disappointing" — Negative

## How to Run
1. Open `Sentiment_Analysis_ML_Project.ipynb`.
2. Click **Open in Colab** or download the notebook and upload it to Google Colab.
3. Run the notebook cells in order.

## Limitations
The model predicts only Positive or Negative sentiment. Neutral reviews may be classified as either category. Predictions are not guaranteed to be correct.

## Author
Machine Learning Project
