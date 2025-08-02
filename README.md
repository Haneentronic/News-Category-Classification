# 📰 News Category Classification

This project is part of my **Elevvo NLP Internship – Task 2**, where I built a machine learning pipeline to automatically classify news articles into specific categories based on their content. The main goal is to explore both supervised and unsupervised natural language processing techniques using real-world news data.

---

## 🚀 Project Overview

The dataset contains news headlines and descriptions categorized into four primary topics:

- 🌍 World  
- 🏈 Sports  
- 💼 Business  
- 🔬 Sci/Tech  

The project consists of:

1. **Text Preprocessing**
   - Lowercasing
   - Tokenization
   - Stopword removal
   - Removing punctuation and non-alphabetic tokens

2. **Feature Engineering**
   - Bag-of-Words with `CountVectorizer`

3. **Modeling**
   - **Naive Bayes Classifier**
   - **XGBoost Classifier**
   - Evaluation using accuracy and classification report

4. **Topic Modeling**
   - **LDA (Latent Dirichlet Allocation)**
   - Topic visualization using `pyLDAvis`

---

## 🛠️ Technologies Used

- Python
- pandas, numpy
- scikit-learn
- XGBoost
- NLTK
- pyLDAvis
- matplotlib, seaborn

---

## 📊 Results

- **Naive Bayes** performed well using CountVectorizer features.
- **XGBoost** gave improved accuracy and precision on most classes.
- **LDA** modeling revealed thematic clusters, aiding content understanding beyond labels.

---

## 📁 Dataset

- Source: [Kaggle News Aggregator Dataset](https://www.kaggle.com/datasets/therohk/million-headlines)

---

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Haneentronic/news-category-classification.git
   cd news-category-classification

2.Install dependencies:

    pip install -r requirements.txt
    
3. Run the notebook:

 Open News_Category_Classification.ipynb in Jupyter Notebook or Google Colab and execute the cells.

 📎 Deliverables

    ✅ Exploratory Data Analysis (EDA)

    ✅ Supervised Learning with Naive Bayes and XGBoost

    ✅ Unsupervised Topic Modeling with pyLDAvis

📌 Internship

This work was completed as part of my Elevvo Natural Language Processing Internship, under Task 2 (News Category Classification & Topic Modeling).


