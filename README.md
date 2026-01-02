# twitter-sentiment-analysis

Twitter Sentiment Analysis using Machine Learning

This project performs **binary sentiment analysis (Positive vs Negative)** on Twitter data using **classical NLP techniques** and **machine learning**.  
The model is trained on the **Sentiment140 dataset** containing **1.6 million tweets**.


Problem Statement
Given a tweet, predict whether the sentiment expressed is **positive** or **negative**.

 Dataset
- **Sentiment140**
- 1.6 million tweets
- Labels:
  - `0` → Negative
  - `1` → Positive
- Dataset link: http://help.sentiment140.com/for-students

The dataset is not included in this repository due to size constraints.

Tech Stack
- Python
- Pandas & NumPy
- NLTK (text preprocessing)
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression

Project Workflow
1. Load and inspect dataset  
2. Convert labels (4 → 1 for positive sentiment)  
3. Text preprocessing:
   - Lowercasing
   - Removing special characters
   - Stopword removal  
4. Feature extraction using **TF-IDF (unigrams + bigrams)**  
5. Train-test split with stratification  
6. Model training using **Logistic Regression**  
7. Model evaluation and saving  

odel Performance

| Metric | Score |
|------|------|
| Training Accuracy | 76.97% |
| Test Accuracy | **76.76%** |

✔ Minimal overfitting  
✔ Good generalization  
✔ Fast training time  
Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix






