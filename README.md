# GlassdoorSentimentAnalysis
Capstone Project for General Assembly Data Science Immersive Bootcamp

Glassdoor is a social media forum for sharing thoughts and opinions about workplaces. This is a kaggle dataset of reivews of big tech firms- Google, Facebook, Amazon, Netflix and Microsoft. But the company labels themseleves are stripped out before feeding into model production so they will not be used in the prediction.


# Data Cleaning
- Text pre-processing
- Removing non-english reviews
- Cleaning dates and converting location to country

# EDA
- Labeling dataset: classifying into positive, neutral and negative reviews
- Checking importance of and selecting non-textual features that might be correlated with the output variable to later to be used in the predictive model


# Sentimen Prediction
- comparing vectorization models
- resampling to tackle class imbalance
- textual feature comparison and selection such as n-grams
- The model achieved score of 94% xx times better than the baseline
