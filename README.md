# SMS Spam Classification

This project is about classifying SMS messages as spam or ham using machine learning and natural language processing.

## About the Project

The project uses the SMS Spam Collection dataset. I started by exploring the data, checking for missing values and duplicates, and looking at the distribution of spam and ham messages.

After that, I cleaned the text by converting it to lowercase, removing unnecessary characters, and removing duplicate messages.

For feature extraction, I used TF-IDF with unigrams and bigrams to convert the text into numerical features.

## Models

I trained and compared three different machine learning models:

* Multinomial Naive Bayes
* Logistic Regression
* Support Vector Machine (SVM)

The models were evaluated using classification reports, including precision, recall, and F1-score. I also used a confusion matrix to get a better understanding of the model predictions.

## Tools and Libraries

* Python
* Pandas
* Scikit-learn
* NLTK
* Matplotlib
* Seaborn
* KaggleHub

## Dataset

The dataset used in this project is the SMS Spam Collection Dataset from Kaggle.

It contains SMS messages labeled as either spam or ham.

## Project Workflow

1. Load the dataset
2. Explore and understand the data
3. Clean and preprocess the text
4. Convert text into TF-IDF features
5. Split the data into training and testing sets
6. Train different machine learning models
7. Evaluate and compare the results

## Conclusion

The main goal of this project is to build a simple spam detection system and understand how different machine learning models perform on text classification problems.

