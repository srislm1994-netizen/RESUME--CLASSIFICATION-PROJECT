This project focuses on Resume Classification using Natural Language Processing (NLP) and Machine Learning. The main objective is to automatically classify resumes into different job categories based on their content. Manual resume screening is time-consuming, so this system helps recruiters save time and effort.

The dataset used for this project was collected from Kaggle (Resume Dataset). The resume text was first cleaned by removing special characters, stopwords, and converting text to lowercase. After preprocessing, TF-IDF (Term Frequency–Inverse Document Frequency) was used to convert text data into numerical features.

A Linear Support Vector Machine (Linear SVM) model was trained on the processed data. The dataset was split into training and testing sets to evaluate model performance. The trained model achieved an accuracy of approximately 95%, showing strong performance in classifying resumes correctly.

This project demonstrates how NLP and machine learning techniques can be effectively used in real-world recruitment systems to automate resume screening and improve hiring efficiency.
