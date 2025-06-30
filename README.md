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
