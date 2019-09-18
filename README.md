# Glassdoor Sentiment Analysis
Capstone Project for General Assembly Data Science Immersive Bootcamp

Glassdoor is a social media forum for sharing thoughts and opinions about workplaces. The aim of this project was to predict the sentiment of a glassdoor review as being positive, negative or neutral based on the available features. After labeling and exploring the dataset, the project became a text classification problem to classify a review as positive, neutral or negative based on features in the text alone. The other non-textual variables in the dataset did not show to be significantly correlated with the overall sentiment of a review which includes the summary headline, pros, cons and advice to management sections. The company labels are stripped out before feeding into model production so they will not be used in the prediction.

This is a kaggle dataset of reivews of big tech firms- Google, Facebook, Amazon, Netflix and Microsoft. Thus, the model might be highly contextual (one industry). The project code is in Python. 


# Data Cleaning
- Text pre-processing
- Removing non-english reviews
- Cleaning dates and converting location to country

# EDA
- Labeling dataset: classifying into positive, neutral and negative reviews
- Checking statistical significance of non-textual features that might be correlated with the output variable to later to be used in the predictive model

# Sentimen Prediction
- Resampling to tackle class imbalance
- Textual feature comparison such as n-grams, number of word features and vectorizers
- Random forest classifier to classify reviews
- Visualizing model performance with various features specified
- The best model achieved a score of 99% which is 9.92% times better than the baseline

# Data
- All the data filtered at various stages of the project, including the original dataset can be found in this folder
