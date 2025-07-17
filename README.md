# 💬 Sentiment Analysis using Machine Learning & NLP

This project performs **sentiment analysis** on restaurant reviews using **Natural Language Processing (NLP)** and **Machine Learning** techniques. It classifies reviews as **Positive** or **Negative**, helping businesses understand customer feedback effectively.

---

## 🚀 Features
- Preprocesses text data (tokenization, stopword removal)
- Converts text to numeric form using **Bag of Words**
- Trains a **Naive Bayes Classifier** for sentiment prediction
- Includes ready-to-use trained models (`.pkl` files)
- Works on new datasets for **batch predictions**
- Jupyter notebooks for training, prediction, and visualization

---

## 🛠️ Technologies Used
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Jupyter Notebook / VS Code

---

## 📁 Project Files Overview

| File Name                             | Description |
|--------------------------------------|-------------|
| `a1_RestaurantReviews_HistoricDump.tsv` | Dataset used for model training |
| `a2_RestaurantReviews_FreshDump.tsv`    | Fresh reviews for prediction |
| `b1_Sentiment_Analysis_Model.ipynb`     | Jupyter Notebook for model building & training |
| `b2_Sentiment_Predictor.ipynb`          | Notebook for using trained model on new reviews |
| `c1_BoW_Sentiment_Model.pkl`            | Saved Bag-of-Words model (Vectorizer) |
| `c2_Classifier_Sentiment_Model.pkl`     | Trained Naive Bayes classifier |
| `c3_Predicted_Sentiments_Fresh_Dump.tsv`| Output TSV with predicted sentiments |
| `requirements.txt`                      | Python dependencies for the project |

---

## ⚙️ How to Run Locally

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/sentiment-analysis-nlp.git
cd sentiment-analysis-nlp
