# 📰 Fake News Detection using Machine Learning

This project focuses on detecting fake news using a supervised machine learning approach. The model is trained to classify whether a given news article is **real** or **fake** based on its content.

## 📌 Project Summary

Fake news is a major issue in today's digital world. This project leverages machine learning techniques to identify misleading or false content from real news using **text classification** methods.

## 🧠 Algorithm Used
- **Passive Aggressive Classifier** – an efficient, online learning algorithm ideal for large-scale text classification.

## 📂 Dataset
- **Source**: `news.csv`
- **Features**:
  - `text` – The body/content of the news article
  - `label` – `FAKE` or `REAL`

## 📊 Evaluation
- **Train/Test Split**: 80/20
- **Accuracy Achieved**: 84%

## 🛠️ Technologies Used
- Python
- Pandas
- Scikit-learn
- TfidfVectorizer (for text feature extraction)

## 🧪 How to Run
1. Clone the repo or open the notebook in Google Colab
2. Ensure `news.csv` is in the same directory
3. Run all cells in the Jupyter Notebook

## 📓 Files
- `Fake_News_Detection.ipynb`: Main notebook with code and output
- `news.csv`: Dataset file (if not available, download from Kaggle or source link)

## ✅ Key Highlights
- Text pre-processing using **TF-IDF Vectorization**
- Trained a robust model with **Passive Aggressive Classifier**
- Evaluated with accuracy score and confusion matrix
