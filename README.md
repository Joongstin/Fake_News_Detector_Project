# Fake News Detector Project 
### Objective
The objective of this project is to determine whether news that we encounter in daily life is fake or not using Natural Language Processing (NLP). Because we often encounter news that can possibly contain false information intended to manipulate public media or extend particular ideas to  achieve political agenda. Such news may contain wrong or exaggerated items, and users may end up consuming fake news that they perceive to be true. In this project, we will use some Python libraries to analyze the news data and extract some features from corresponding data to detect the fake news.

### Techniques/Tools
- Regex (Regular Expression) - Remove all punctuations
- NLTK (Natural Language Toolkit) Libraries 
  - Tokenization 
  - Stopwords
  - Lemmatization 
- NLP (Natural Language Processing) Techniques
  - Sklearn Feature Extraction Library 
    - CountVectorizer 
    - TF-IDF 
  - Sklearn Modeling 
    - Logistic Regression
    - Multinomial Naive Bayes 

### Data Cleanup & Feature Extraction

![image](https://user-images.githubusercontent.com/89524942/166177491-4a278d96-3ef2-4678-a7c7-478cd30d5479.png)

- Performed feature engineering in our datasets that will be used for modeling 

### Modeling 
- Used two classifiers:
  - Logistic Regression Classifier
  - Naïve-Bayes Classifier

- Confusion Matrix 
![image](https://user-images.githubusercontent.com/89524942/166177870-a64283b1-d20b-4a9c-9a1d-324f1e3fbb8f.png)

### Prediction 
![image](https://user-images.githubusercontent.com/89524942/166177978-93aa59a3-2ce2-41fa-8250-c6d67332dfe5.png)

### Brief Conclusion
Each section shown above demontrates the general flow of the project. The detailed explanation, especially the feature extraction, is included in pdf report attached in the file. For the sake of simplicity, we only chose two classifiers to mostly compare how the machine learning works in confusion matrix and how it is applied when creating the pipeline accordingly. If we were to choose one model, it would have been a logistic regression model based on balanced amount of both False Postivies and False Negatives in a confusion matrix. However, we decided to fit both models and predict them to see the result for the educational purpose.
