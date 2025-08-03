# 📦 Flipkart Customer Reviews – Sentiment Analysis (NLP Project)

This project applies **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques to analyze and classify customer reviews from **Flipkart**, one of India's largest e-commerce platforms. The main goal is to categorize each review into one of three sentiments: **Positive**, **Negative**, or **Neutral**, and extract actionable insights for business strategy.

---

## 📌 Project Overview

- **Domain**: E-commerce
- **Technique**: NLP + ML
- **Dataset**: Public reviews from Flipkart (collected over 5 years)
- **Models Used**: Logistic Regression and Random Forest
- **Goal**: Predict customer sentiment, evaluate model performance, and visualize trends

---

## 🧠 Objectives

1. **Sentiment Categorization**  
   Classify customer reviews into Positive, Negative, or Neutral.

2. **Model Comparison**  
   Evaluate and compare the performance of Logistic Regression and Random Forest.

3. **Visualization & Insights**  
   Use data visualization (e.g., WordClouds, sentiment distribution, rating analysis) to gain business insights.

4. **Actionable Recommendations**  
   Understand sentiment patterns to guide marketing and customer service strategies.

---

## 🧾 Dataset

- **Source**: [Kaggle - Flipkart Reviews Sentiment Analysis](https://www.kaggle.com/code/amirmotefaker/flipkart-reviews-sentiment-analysis)
- **Features**:
  - Review Text
  - Rating (1–5 stars)
  - Product Category
  - Timestamp

---

## 🛠️ Methodology

### 1. Data Preprocessing
- Duplicate removal
- Spam filtering
- Language filtering (English only)
- Noise reduction
- Tokenization
- Stopword removal (NLTK)
- Lemmatization
- Lowercasing and normalization

### 2. Feature Engineering
- Bag-of-Words (BoW)
- TF-IDF
- N-Grams (bigrams & trigrams)
- Dimensionality reduction (top 5000 features)

### 3. Sentiment Classification Models
- **Logistic Regression**:
  - Simplicity and interpretability
  - Performs well for linearly separable data
- **Random Forest**:
  - Handles non-linear relationships
  - Reduces overfitting using ensemble learning

---

## 📊 Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **Confusion Matrix**

---

## 📈 Visualization Tools

- **Matplotlib**: Standard plots and confusion matrices  
- **Seaborn**: Statistical data visualizations  
- **WordCloud**: Highlights most frequent sentiment-related words  
- **Bar Charts**: Sentiment distribution, rating overview  
- **Boxplots**: Comparison between sentiment and ratings

---

## 🔍 Results & Analysis

### Sentiment Distribution:
- Positive: 4,164 reviews (≈85.6%)
- Negative: 595 reviews (≈12.2%)
- Neutral: 174 reviews (≈2.2%)

### Model Performance:

| Metric         | Logistic Regression | Random Forest  |
|----------------|---------------------|----------------|
| Accuracy       | 91.08%              | **91.59%**     |
| Precision      | **0.90**            | 0.89           |
| Recall         | 0.91                | **0.92**       |
| F1 Score       | **0.91**            | 0.90           |

- Random Forest performs slightly better in recall and accuracy
- Logistic Regression is slightly more precise and balanced

### Sentiment vs Rating Correlation:
- Positive reviews correlate well with 4–5 star ratings
- Negative reviews mostly have 1–2 stars
- Neutral reviews span all ratings

---

## 💡 Key Insights

- Products like **Bluetooth Headsets**, **Air Coolers**, and **boAt/Crompton** brands receive highly positive feedback.
- Frequent issues include **battery life**, **delivery delays**, and **build quality**.
- Visualization helps businesses focus on **high-performing products** and **customer pain points**.

---

## 📁 Project Structure

