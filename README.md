# Stock-Trading-App-Review
## 🎯 Objective

To predict the sentiment (positive/neutral/negative) of user reviews using supervised machine learning, enabling:

- App performance monitoring
- User feedback mining
- Comparative analysis of trading platforms

---

## 🧪 Technologies Used

- Python, Pandas, NumPy
- Scikit-learn
- TF-IDF Vectorization
- SMOTE (for class imbalance)
- Models:
  - Logistic Regression
  - Random Forest
- Evaluation:
  - Accuracy, F1-score, Classification Report
  - Confusion Matrix

---

## 🧰 Steps Performed

1. **Data Cleaning** (null removal, score-to-sentiment mapping)
2. **Text Preprocessing** (lowercasing, punctuation removal)
3. **Feature Engineering** (TF-IDF)
4. **Train-Test Split** (with stratification)
5. **Imbalanced Class Handling** using SMOTE
6. **Model Training & Evaluation**
7. **Model Comparison & Interpretation**

---

## 🧠 Key Findings

- **XGBoost** showed the best performance overall, especially for positive and negative classes.
- **Neutral sentiment** remains the hardest to classify due to limited and overlapping data.
- **SMOTE** helped improve balance, but further improvement could come from BERT or transformer models.

---

## 📌 Future Improvements

- Use deep learning (e.g., BERT or DistilBERT)
- Enhance preprocessing (emoji handling, lemmatization)
- Increase labeled data for neutral reviews
