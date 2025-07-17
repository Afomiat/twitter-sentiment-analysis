# 🐦 Twitter Sentiment Analysis (Positive/Negative)

This project explores how Artificial Intelligence (AI) and Machine Learning (ML) can be applied to real-world problems using a classic example: **Twitter Sentiment Analysis**.

The goal is to build a machine learning model that classifies tweets as **positive** or **negative**, helping to understand public opinion in social media. I chose this project to gain hands-on experience and understand how AI/ML works in practice—covering data preprocessing, feature extraction, model training, and evaluation.

---

## 📂 Dataset

- **Source**: [Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140)  
- **Size**: 1.6 million labeled tweets  
- **Labels**: `positive`, `negative` (binary classification)

---

## 🛠️ Technologies & Libraries Used

- Python
- Google Colab
- Pandas
- Scikit-learn
- NLTK
- TF-IDF Vectorizer
- Logistic Regression

---

## 🔄 Project Workflow

1. Load and clean tweet data  
2. Preprocess text (lowercasing, removing stopwords, etc.)  
3. Extract features using **TF-IDF Vectorizer**  
4. Train **Logistic Regression** model  
5. Evaluate the model on training and test datasets  

---

## 📊 Results

- **Accuracy on Training Data**: `79.87%`  
- **Accuracy on Test Data**: `77.67%`

The model generalizes well and shows decent performance on a large dataset using a simple algorithm.

---

## 🚀 What I Learned

- How to work with large NLP datasets  
- How to clean and preprocess tweet data (handling noise, punctuation, etc.)  
- How feature extraction works in text classification  
- Building and evaluating a logistic regression model  
- Understanding real-world ML pipeline end-to-end

---

## 🔮 Future Improvements

If I had more time or resources, I would:
- Experiment with more advanced models (e.g., LSTM, BERT)
- Handle emojis, hashtags, and sarcasm
- Create a simple web interface or API for real-time sentiment analysis

---

## 🧠 How to Use

1. Clone this repository  
2. Open the notebook `twitter_sentiment_analysis.ipynb` in Google Colab or Jupyter Notebook  
3. Run all cells to see results  

---

## 👤 Author

**Afomia Tadesse**  
📫 afomiat79@gmail.com


