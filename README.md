# 🎬 Sentiment Analysis on IMDB Movie Reviews using NLP & Machine Learning

> A Natural Language Processing (NLP) project that classifies IMDB movie reviews as **Positive** or **Negative** using text preprocessing, TF-IDF vectorization, and the Multinomial Naive Bayes algorithm.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![NLP](https://img.shields.io/badge/NLP-Sentiment%20Analysis-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

# 📖 Project Overview

Sentiment Analysis is one of the most popular applications of Natural Language Processing (NLP). It is used to determine whether a piece of text expresses a **positive** or **negative** opinion.

In this project, an IMDB Movie Reviews dataset is preprocessed using NLP techniques, transformed into numerical features using **TF-IDF Vectorization**, and classified using the **Multinomial Naive Bayes** algorithm.

The trained model can also predict the sentiment of custom movie reviews entered by the user.

---

# 🎯 Objectives

- Build a sentiment classification model for movie reviews.
- Perform text preprocessing using NLP techniques.
- Convert text into numerical vectors using TF-IDF.
- Train a machine learning model for sentiment prediction.
- Evaluate the model using standard classification metrics.
- Predict sentiment for custom user reviews.

---

# ✨ Features

- ✔ Text preprocessing
- ✔ Stopword removal
- ✔ Stemming using Porter Stemmer
- ✔ TF-IDF Vectorization
- ✔ Train-Test Split
- ✔ Multinomial Naive Bayes Classifier
- ✔ Confusion Matrix
- ✔ Classification Report
- ✔ Accuracy Score
- ✔ Sentiment Distribution Visualization
- ✔ Custom Review Prediction

---

# 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| Language | Python |
| Notebook | Jupyter Notebook |
| NLP | NLTK |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |

---

# 📂 Project Structure

```
Sentiment-Analysis-IMDB/
│
├── project_5.ipynb
├── IMDB Dataset.csv
├── README.md
└── requirements.txt
```

---

# 🔄 Project Workflow

### Step 1 – Import Libraries

Import all required libraries for NLP, visualization, preprocessing, and machine learning.

---

### Step 2 – Load Dataset

Load the IMDB Movie Reviews dataset using Pandas.

---

### Step 3 – Explore Dataset

- Check dataset shape
- View sample records
- Check missing values
- Understand sentiment distribution

---

### Step 4 – Text Preprocessing

Each review is cleaned using NLP techniques:

- Convert text to lowercase
- Remove special characters
- Remove stopwords
- Apply Porter Stemming

This improves the quality of text features used for training.

---

### Step 5 – Feature Extraction

Convert cleaned reviews into numerical vectors using **TF-IDF (Term Frequency–Inverse Document Frequency)**.

---

### Step 6 – Train-Test Split

Split the processed dataset into training and testing sets.

---

### Step 7 – Train Machine Learning Model

Train the **Multinomial Naive Bayes** classifier using the TF-IDF features.

---

### Step 8 – Model Evaluation

Evaluate the trained model using:

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score
- Classification Report

---

### Step 9 – Visualization

Generate visualizations including:

- Sentiment Distribution
- Confusion Matrix Heatmap

---

### Step 10 – Predict Custom Reviews

The trained model accepts custom movie reviews and predicts whether the sentiment is **Positive** or **Negative**.

---

# 🤖 Machine Learning Algorithm

- Multinomial Naive Bayes

---

# 📊 Evaluation Metrics

The model performance is evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

# 📈 Visualizations

The notebook includes:

- Sentiment Distribution Graph
- Confusion Matrix Heatmap

---

# 📚 Dataset

This project uses the **IMDB Movie Reviews Dataset**, containing thousands of movie reviews labeled as:

- Positive
- Negative

The dataset is widely used for NLP and sentiment analysis tasks.

> Note: The dataset may not be included in this repository due to GitHub file size limitations.

---

# 🚀 How to Run

### Clone the Repository

```bash
git clone https://github.com/yourusername/Sentiment-Analysis-IMDB.git
```

### Navigate to the Project Folder

```bash
cd Sentiment-Analysis-IMDB
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn nltk scikit-learn
```

### Run the Notebook

```bash
jupyter notebook project_5.ipynb
```

Run all cells in sequence.

---

# 💡 Future Improvements

- Try Logistic Regression and SVM for comparison.
- Use Word2Vec or GloVe embeddings.
- Implement LSTM or BERT for deep learning-based sentiment analysis.
- Deploy the model using Streamlit or Flask.
- Build a web application for real-time sentiment prediction.

---

# 🎓 Learning Outcomes

Through this project, I learned:

- Natural Language Processing (NLP)
- Text preprocessing techniques
- Stopword removal
- Stemming
- TF-IDF Vectorization
- Text classification
- Model evaluation
- Sentiment prediction
- Data visualization

---

# 👨‍💻 Author

**Hemang Chouhan**

B.Tech – Computer Science Engineering (Artificial Intelligence & Data Science)

Passionate about Artificial Intelligence, Machine Learning, Natural Language Processing, and Data Science.

---

## ⭐ If you found this project useful, consider giving it a Star!
