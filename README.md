# Sentiment Analysis on Movie Reviews 🎬🧠

This Natural Language Processing (NLP) project analyzes sentiment in movie reviews using the Kaggle Rotten Tomatoes dataset. The objective is to classify phrases into five sentiment categories using preprocessing, feature engineering, and machine learning models.

---

## 📌 Project Highlights

- **Dataset:** 156,060 labeled phrases from Rotten Tomatoes
- **Sentiment Labels:**  
  - 0: Negative  
  - 1: Somewhat Negative  
  - 2: Neutral  
  - 3: Somewhat Positive  
  - 4: Positive
- **Models Used:** Naive Bayes, Support Vector Machine (SVM), Random Forest
- **Best Result:** 55% accuracy using SVM with filtered Unigram + POS features

---

## 🧰 Techniques & Tools

### 🔹 Text Preprocessing
- Lowercasing, punctuation removal, tokenization (NLTK)
- Stop-word filtering (default + custom domain-specific)
- Word filtering by token length

### 🔹 Feature Engineering
- Unigrams, Bigrams, Trigrams
- POS tag counts (Nouns, Verbs, Adjectives, Adverbs)
- Sentiment Lexicons (LIWC, Subjectivity Lexicon)
- Combined feature sets

### 🔹 Model Evaluation
- Accuracy comparison across classifiers
- 5-fold Cross-validation
- Filtered vs. Unfiltered feature performance

---

## 📁 Repository Structure
📦 sentiment-analysis-movie-reviews/
├── classifykaggle.ipynb               # Main Jupyter notebook
├── *.py                               # Feature extraction scripts
├── *.csv                              # Preprocessed & feature-engineered data
├── SentimentLexicons/                # Lexicon dictionaries
├── FINAL NLP REPORT.docx             # Full academic report
└── README.md                          # Project overview


---

## 📈 Results Summary

| Classifier      | Accuracy (Best Case) | Best Features         |
|----------------|----------------------|------------------------|
| **SVM**         | 55%                  | Filtered Unigram + POS |
| Random Forest   | 54%                  | Filtered POS           |
| Decision Tree   | 51%                  | Filtered POS           |

> Preprocessing consistently improved performance across all models.

---

## 🚀 Future Enhancements

- Integrate TF-IDF, GloVe, or BERT embeddings
- Expand to deep learning models (LSTM, Transformers)
- Build a web app using Streamlit or Flask

---

## 👨‍💻 Author

**Kartik Trisal**  
_Data Analyst  
[GitHub](https://github.com/kartiktrisal) | [LinkedIn](https://linkedin.com/in/kartiktrisal)

