# NLP-assignment
Aim:  Develop machine learning models (Naive-Bayes and Support Vector Machine) to classify emotions in text samples.

Dataset:   https://drive.google.com/file/d/1HWczIICsMpaL8EJyu48ZvRFcXx3_pcnb/view?usp=drive_link

Dataset Analysis: 
    Rows= 5937 ,Columns= 2
    Null values= 0
    Duplicates=0

Data Pre-processing:
    Feature and Target are identified. Feature is converted into a list.
    Tokenization- Word Tokenization is carried out.
    Tokens are transformed into lower case format.
    Stopwords are removed from the tokens.
    Lemmatization is carried out on the tokens.
    Punctuations are removed from the lemmatized tokens.
    The cleaned data is joined to make a corresponding sentence.

Feature Extraction:
    TfidfVectorizer is used for feature extraction.

Model Implementation: 
    Since the target variable belongs to a classification type, classification models are to be used.
    1. Naive-Bayes
    2. Support Vector Machine

Results:
    Accuracy Score: Naive-Bayes= 57% approx, SVM= 92% approx
    f1-score: Naive-Bayes= 0.569071, SVM= 0.925108
    precision: Naive-Bayes= 0.580704, SVM= 0.926721
    recall: Naive-Bayes= 0.569697, SVM= 0.925253
    Support Vector Classifier is a superior model when compared with Naive-Bayes.
