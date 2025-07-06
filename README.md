# 🧠 Disease Prediction from Symptoms

This project uses Natural Language Processing (NLP) to predict diseases based on a list of patient-reported symptoms. The goal is to explore how transformer-based embeddings (like BERT) can improve diagnosis accuracy compared to traditional models.

## ✅ Current Features

- ✅ **Dataset**: Kaggle - [Disease Prediction from Symptoms](https://www.kaggle.com/datasets/itachi9604/disease-symptom-description-dataset)
- ✅ **Preprocessing**:
  - Combined symptoms into a single string
  - Cleaned and lemmatized using `spaCy`
- ✅ **Embeddings**:
  - Used `bert-base-uncased`
  - Extracted `[CLS]` token from last hidden state
- ✅ **Model**:
  - Trained a `RandomForestClassifier` on BERT embeddings
  - Achieved **100% accuracy** on test data
- ✅ **Evaluation**:
  - Accuracy, classification report, and confusion matrix

## 📊 Performance

- **Accuracy**: `1.00`  
- **Model**: Random Forest (trained on BERT CLS embeddings)  
- **Embedding Shape**: `(4920, 768)`

## 🔧 Tools Used

- `transformers` by HuggingFace
- `scikit-learn`
- `spaCy`
- `pandas`, `numpy`, `matplotlib`

---
