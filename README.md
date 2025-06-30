# SENTIMENT-ANALYSIS

COMPANY : CODTECH IT SOLUTIONS

NAME : Pulikonda Tapaswi

INTERN ID : CT2MTDM339

DOMAIN : Machine Learning

DURATION : 8 WEEKS

MENTOR : NEELA SANTOSH

# DESCRIPTION

This project is to analyze a dataset of customer reviews and build a model that classifies them into positive or negative sentiments. The model uses TF-IDF (Term Frequency-Inverse Document Frequency) vectorization for converting text to numerical form and applies Logistic Regression for classification.

# Tools and Technologies:
Language: Python
Libraries:
pandas – data manipulation
numpy – numerical processing
sklearn – machine learning model, TF-IDF, metrics
matplotlib / seaborn – for visualizations

# Project Workflow:
1. Load and Explore Data
Read the dataset using pandas
Display sample reviews
Analyze class distribution
2. Preprocess Text
No need for manual cleaning as TF-IDF handles most preprocessing
Use TfidfVectorizer from sklearn.feature_extraction.text to convert text into numerical vectors
3. Train-Test Split
   Split the dataset into 80% training and 20% testing sets using train_test_split
4. Train Logistic Regression Model
Use LogisticRegression from sklearn.linear_model to fit the TF-IDF-transformed training data
Predict sentiment for test data
5. Evaluate the Model
Generate metrics like accuracy, precision, recall, and F1-score
Plot confusion matrix using seaborn.heatmap

# OUTPUT

![Image](https://github.com/user-attachments/assets/b3907feb-9a67-44c7-8433-bdca9553370e)

![Image](https://github.com/user-attachments/assets/081a9070-5d8e-4390-b9f7-a2a4d0dde442)
