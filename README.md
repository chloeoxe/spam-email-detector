# spam-email-detector

## Project Description
This project details the various steps that I took to build my own spam email classifier that is able to classify an email as spam or non-spam(ham) via a set of its features. 

I obtained the dataset for this project through Kaggle: https://www.kaggle.com/datasets/nitishabharathi/email-spam-dataset?resource=download. In particular, I have used the 'completeSpamAssassin.csv' dataset for this project. It simply includes a serial number column that can be used as the index, a body column that contains the actual text content of each email, and the label column that is 0 for ham emails and 1 for spam emails as seen in the figure below.

![Screenshot 2023-02-14 at 10 06 24 PM](https://user-images.githubusercontent.com/97609174/218761794-1de1ca89-7967-4c11-8e50-c9ca11139f84.png)



From the dataset, it is straightforward that we may use a vectorizer (count/TD-IDF) to extract features from the email body column. However, for this project, I have implemented some feature engineering to attempt at producing more features (in addition to the ones extracted from a TF-IDF vectorizer) that can enhance the performance of the spam email classifier. I have also implemented several different Machine Learning algorithms to identify the best one.

Topics covered in this project are:
- Supervised Machine Learning
- Binary Classification
- Natural Language Processing
- Data Visualisation
- Data Manipulation & Analysis
- Feature Engineering
- Model Evaluation
