# amazon-product-review-NLP
NLP Project: Sentiment and Topic Analysis on Amazon Product Reviews

# 🛒 Amazon Product Review Sentiment Analysis (NLP Project)

This project performs sentiment analysis on Amazon product reviews using Natural Language Processing (NLP). The goal is to classify reviews as **positive**, **neutral**, or **negative** based on their content and star rating.


## 📊 Dataset

- **Source**: [Kaggle - Amazon Fine Food Reviews](https://www.kaggle.com/snap/amazon-fine-food-reviews)
- **Shape**: 568,000+ reviews
- **Columns**: Review Text, Score, Product/User Info, Time, etc.

## 🧹 Data Cleaning

- Removed duplicate review texts
- Dropped rows with null `Text` or `Score`
- Added a new `Sentiment` column based on:
  - `Score >= 4` → **Positive**
  - `Score == 3` → **Neutral**
  - `Score <= 2` → **Negative**

## 📈 Exploratory Data Analysis (EDA)

- Distribution of sentiment labels
- Review length statistics
- Word clouds (optional)
- Token frequency (optional)

## 🧠 Model (Planned)

| Model              | Description              |
|-------------------|--------------------------|
| Logistic Regression | Baseline model          |
| Naive Bayes        | Simple probabilistic model |
| TF-IDF + SVM       | Advanced vector-based model |
| BERT (optional)    | Transformer-based deep model |

## 📌 TODO

 Clean & preprocess data

 Add sentiment labels

 Visualize sentiment distribution

 Train baseline models

 Optimize performance

 Try transformer-based NLP models (e.g., BERT)

✍️ Author
Kartik Rane
WStudent Reserach Assistant | Data Engineer & Analyst
📫 https://www.linkedin.com/in/kartik-rane-b122b6190/