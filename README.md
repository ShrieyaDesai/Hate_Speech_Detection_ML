# Hate_Speech_Detection_ML
This repository consists of the Contents of Hate_Speech  Detection Project based on ML models

Social media platforms, if not managed properly, can become a breeding ground for chaos. One of the major issues on these platforms is the usage of hate speech and offensive language. Such language can lead to conflicts, crimes, and, in extreme cases, riots. To combat this, it is essential to detect and prevent the use of such language. Given the massive volume of data, manual monitoring is impractical. Therefore, leveraging AI to detect hate speech is crucial.

This project focuses on building a machine learning model to recognize hate speech and offensive language, helping to mitigate potential harm caused by such content on social media platforms.

# Libraries and Tools Used
### sklearn.feature_extraction: 
Used for extracting features in a format supported by machine learning algorithms from datasets consisting of formats such as text and image.
### CountVectorizer: 
Converts text into vectors for text classification, creating matrices with 0's and 1's, enabling the model to understand the data.
### NLTK (Natural Language Toolkit): 
A platform for building Python programs that work with human language data, useful for tasks like stemming and stopword removal.
### re (Regular Expression): 
Replaces irrelevant text with an empty string, cleaning the data.
### NumPy:
A library for creating arrays, which are grids of values of the same type, indexed by a tuple of nonnegative integers.
# Key Concepts
- Stopwords: Words that do not add much meaning to a sentence and can be ignored without losing the sentence's overall meaning (e.g., "a", "is", "the").
- Stemming: Reducing a word to its base or root form, grouping similar words under a common stem (e.g., "care", "caring", "cared" are all reduced to "care").
- Corpus: A collection of authentic text or audio organized into datasets for training models.
- Decision Tree: A supervised machine learning algorithm that uses a set of rules to make decisions.
# Data Preprocessing
- Text Cleaning: Regular expressions are used to clean the text by removing irrelevant characters or symbols.
- Vectorization: Text data is converted into vectors using CountVectorizer.
- Stopword Removal: Common words that do not contribute much meaning to the text are removed.
- Stemming: Words are reduced to their base form.
# Machine Learning Models Used
Three machine learning models were implemented for hate speech detection, each showing effective results with good accuracy:

- KNeighborsClassifier
- Support Vector Classifier (SVC) Kernel
- Logistic Regression
### Model Evaluation
The dataset was split into 75% training data and 25% test data to evaluate the models. The models performed well, showing promising accuracy in detecting hate speech.

# Conclusion
This project demonstrates the application of machine learning models in recognizing hate speech on social media platforms. By implementing these models, it is possible to automate the detection of offensive language, contributing to a safer online environment.
 
