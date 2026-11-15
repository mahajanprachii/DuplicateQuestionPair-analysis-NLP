# 🚀 Quora Duplicate Question Pairs Detection

## 📌 Overview
An NLP and Machine Learning project to identify whether two Quora questions have similar meanings and classify them as duplicate or non-duplicate.

## 📂 Dataset
[Quora Question Pairs – Kaggle](https://www.kaggle.com/c/quora-question-pairs/data)

## ⚙️ Work Done


- 📊 **Exploratory Data Analysis (EDA):** Analysed duplicate ratios, unique questions, repeated questions and question distributions.
  
- 🛠️ **Feature Engineering:** Created new features including:
  - Character length of both questions.
  - Number of words in each question.
  - Number of common words between questions.
  - Total words in both questions.
  - Word share between the two questions.
    
- 🔤 **Text Vectorization:** Applied Bag of Words (BoW) using CountVectorizer with 3,000 features.
- 📈 **Feature Analysis:** Compared feature distributions for duplicate and non-duplicate question pairs.
- 🤖 **Model Building:** Implemented and evaluated Random Forest and XGBoost classifiers.

## 📊 Model Performance

Models were trained and evaluated using an 80:20 train-test split.

| Model | Accuracy |
|---|---:|
| 🌳 Random Forest Classifier | **76.88%** |
| ⚡ XGBoost Classifier | **76.80%** |

## 🧰 Tech Stack

🐍 Python | 🐼 Pandas | 🔢 NumPy | 📊 Matplotlib | 🎨 Seaborn | 📝 NLTK | 🤖 Scikit-learn | ⚡ XGBoost
