# Spam Email Detection

This is a simple machine learning project that detects whether a message is spam or not spam (ham).

The project is built using Python, NLP preprocessing techniques, TF-IDF vectorization, and the Multinomial Naive Bayes algorithm.

---

## Dataset Used

Spam email Dataset from kaggle

link : https://www.kaggle.com/datasets/jackksoncsie/spam-email-dataset

---

## Libraries Used

- pandas
- numpy
- nltk
- scikit-learn
- matplotlib
- seaborn
- wordcloud

---

## Steps Performed

- Data cleaning
- Text preprocessing
- Stopword and punctuation removal
- Stemming
- TF-IDF vectorization
- Model training using Naive Bayes
- Model evaluation
- Spam prediction on custom messages

---

## Model

Multinomial Naive Bayes

---

## Evaluation Metrics

The model was evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## Files in the Project

- `Spam_email_detection.ipynb` - Main notebook
- `spam.csv` - Dataset
- `model.pkl` - Saved trained model
- `vectorizer.pkl` - Saved TF-IDF vectorizer
- `requirements.txt` - Required libraries

---

## Sample Predictions

Message:
"Win cash prize now!!!" 

Prediction:
Spam

Message:
"Can we meet tomorrow at 5 PM?"

Prediction:
Not Spam

---

## Future Improvements
- Deploy as a web application using Flask or Streamlit
- Use advanced NLP models
- Improve prediction accuracy using larger datasets
- Add real-time email classification

---

## Conclusion

This project helped in understanding how spam detection systems work using Machine Learning and NLP techniques. It also covers the complete workflow from preprocessing to prediction.
