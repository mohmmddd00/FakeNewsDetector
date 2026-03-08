# Fake News Detection System
A Machine Learning pipeline that classifies news articles as "Real" or "Fake" using Natural Language Processing (NLP). This project utilizes a Support Vector Machine (SVM) classifier to distinguish between the linguistic patterns of credible and misleading information.

-> Features
TF-IDF Vectorization: Converts raw text into numerical feature vectors to capture the importance of words across different documents.

SVM Classification: Implements LinearSVC for high-dimensional text classification, providing robust results on text datasets.

Streamlined Pipeline: Includes a seamless integration from raw text input to classification output.

-> Tech Stack
Language: Python

ML Library: scikit-learn

Data Processing: pandas, numpy

-> Project Structure
fakeNewsDetector.ipynb: The primary notebook containing data preprocessing, vectorizer training, and the SVM model implementation.

myNews.txt: A sample text file used to test the model with custom inputs
