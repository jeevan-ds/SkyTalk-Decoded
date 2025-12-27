# SkyTalk-Decoded
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/cbfaca8d-68f8-42be-932d-433d26c15437" />

# SkyTalk-Decoded-Automated-Sentiment-Intelligence-from-Airline-Twitter-Data
SkyTalk Decoded is an NLP-based sentiment analysis project that automatically classifies airline-related tweets into **Positive, Neutral, or Negative** sentiments. The goal is to help airlines monitor customer feedback at scale and gain actionable insights from social media conversations.
The project applies traditional Machine Learning and NLP techniques and evaluates multiple models to identify the best-performing classifier.

---

##  Objectives
- Clean and preprocess raw Twitter text data
- Extract meaningful textual features using TF-IDF
- Build and compare multiple classification models
- Accurately classify customer sentiment into three categories
- Provide data-driven insights for airline service improvement

---

##  Dataset
- **Source:** Airline Twitter data (`tweets.csv`)
- **Records:** ~14,600 tweets
- **Target Variable:** Sentiment (Positive, Neutral, Negative)
- **Data Type:** Unstructured text

---

##  Data Preprocessing
- Text cleaning (lowercasing, removing URLs, mentions, punctuation)
- Tokenization and lemmatization
- Stopword removal
- TF-IDF vectorization for feature extraction

---

## Models Implemented
- Logistic Regression
- Naive Bayes
- Support Vector Machine (SVM)
- **XGBoost Classifier (Final Model)**

---

##  Model Evaluation
- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix

###  Final Model Performance
- **Model:** XGBoost Classifier
- **Accuracy:** ~76%
- Balanced performance across all sentiment classes
- Outperformed a custom-built deep learning neural network

---

##  Key Insights
- Negative sentiment tweets are more frequent and informative
- Machine learning models perform competitively on TF-IDF features
- XGBoost provides strong generalization on noisy social media text

---

##  Tech Stack
- Python
- Natural Language Processing (NLP)
- Scikit-learn
- XGBoost
- Pandas & NumPy
- Matplotlib & Seaborn

---
