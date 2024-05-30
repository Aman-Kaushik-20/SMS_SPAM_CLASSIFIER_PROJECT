# SMS_SPAM_CLASSIFIER_PROJECT
Project Description: SMS Spam Detection

In this project, I developed a machine learning model to detect spam messages in SMS data using Python and several libraries such as Pandas, NLTK, and Scikit-learn. The project involved the following key steps:

Data Acquisition and Preprocessing: Utilized the Pandas library to import SMS data and preprocess it for analysis. This involved cleaning the data by removing special characters and converting text to lowercase.

Text Cleaning and Tokenization: Employed regular expressions and NLTK library to clean the text data. Removed stopwords and applied stemming to reduce words to their root form, which helps in improving the efficiency of the model.

Feature Extraction: Created a Bag of Words model using the CountVectorizer from Scikit-learn to convert text data into numerical features. This step transformed the text data into a matrix of token counts, which serves as input for the machine learning model.

Model Training: Employed the Naive Bayes classifier from Scikit-learn to train the model. This classifier is well-suited for text classification tasks.

