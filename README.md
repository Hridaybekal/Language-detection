# Language-detection

This project is a language detection model that classifies text into different languages using a Naive Bayes classifier. 
The model is built using Python libraries such as Scikit-learn, Pandas, and Seaborn. 
The model preprocesses text data, converts it into a bag-of-words representation, and trains on the dataset to predict the language of a given text.

Installation
To run this project, you'll need to install the required libraries:

pip install pandas numpy seaborn matplotlib scikit-learn

Dataset: any language data from kaggle should work

The key steps in the code include:

Data Preprocessing:
Import the dataset.
Clean the text by removing symbols, numbers, and converting to lowercase.
Convert the categorical language labels into numerical values using LabelEncoder.

Bag of Words:
Convert the preprocessed text into numerical features using the CountVectorizer.

Train-Test Split:
Split the dataset into training and testing sets.

Model Training:
Train the Naive Bayes model using the training data.

Prediction:
Predict the language of a given text.


Link to the notebook: https://colab.research.google.com/drive/1W9nYO0XVDTp-XIXWUl6-1W8HW0Sumw9m?usp=sharing
