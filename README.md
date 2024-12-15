# Fake News Classification App with Sentiment Analysis 

## Overview
The Fake News Classification System is a Deep learning with machine learning Models, designed to identify and classify fake news articles accurately while having sentiment analysis to the news. Using cutting-edge Natural Language Processing (NLP) techniques and mahine and deep learning models, the application aims to combat misinformation and provide reliable tools for content verification.

---

## Features
- **Fake News Detection**: Determines whether a given news article is authentic or fake.
- **User-Friendly Interface**: Simple and intuitive interface for submitting articles and viewing results.
- **Real-Time Classification**: Processes news articles quickly to provide classification results within seconds.
- **Accuracy Tracking**: Evaluates and tracks the model's performance using precision, recall, and F1 score.

---
## Algorithms and Models Used
1. **Logistic Regression**:
   - Applied as an initial baseline model to compare results.
2. **Natural Language Processing (NLP) Tools**: 
   - Tokenization, stemming, and lemmatization for preprocessing text data.
3. **Convolutional Neural Network (CNN)**:
   - Used as the deep learning model for sequence classification tasks.
   - Captures spatial and hierarchical patterns in text data for better performance.

---

## Functionality
1. **Input News Text**: Users provide the text of a news article they want to classify.
2. **Preprocessing**: The system tokenizes and cleans the input text for better model performance.
3. **Prediction**: The trained CNN-based model predicts whether the article is fake or authentic.
4. **Output Results**: The system displays the classification results along with a confidence score.
5. **Performance Tracking**: Ongoing evaluation to measure model improvements over time.

---

## Technologies Used
- Python
- CNN
- Scikit-learn
- Pandas, Numpy
- Flask (for deploying a web application)

---

## How to Use
1. Clone this repository.
2. Install the required dependencies using:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python app.py
   ```
4. Access the web application via `http://localhost:5000`.
5. Submit a news article for classification and view the results.

---

## Future Improvements
- Add multilingual support for global usability.
- Incorporate real-time web scraping for news verification.
- Enhance model performance using ensemble learning methods.

---


