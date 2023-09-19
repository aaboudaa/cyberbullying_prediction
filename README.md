# cyberbullying_prediction
This machine learning project demonstrates the potential of machine learning in identifying and categorizing cyberbullying behavior in text data.

## Description:
The "Cyberbullying Prediction" project focuses on developing a machine learning model to predict instances of cyberbullying in text data, specifically tweets. This project addresses the crucial issue of identifying and classifying different types of cyberbullying behavior, such as those related to gender, religion, age, ethnicity, and others.

You can find the .CSV file in the link below : 👇👇👇👇

https://drive.google.com/file/d/1Mxrb8OsnRix_-Nh6v9iCAF3tia0GxobP/view

## Key Steps and Insights:
**1. Data Preprocessing:** The project begins with loading and preprocessing the dataset, which contains tweet text and corresponding labels for different types of cyberbullying. Data cleaning techniques are applied, including the removal of hashtags, mentions, URLs, and stopwords. Text is also lemmatized to reduce word variations.

**2. Label Encoding:** Cyberbullying types are encoded into numerical values for classification purposes. Each type is mapped to a unique numerical label.

**3. Feature Engineering:** Text data is transformed into numerical features using Count Vectorization. This technique represents text data as a matrix of word frequencies, enabling machine learning models to work with the data.

**4. Model Building:** A Random Forest Classifier is chosen as the classification model for predicting cyberbullying types based on tweet text. The model is trained on the transformed text data.

**5. Model Evaluation:** The project evaluates the model's performance using accuracy as a metric. The accuracy score indicates how well the model predicts the correct cyberbullying type.
