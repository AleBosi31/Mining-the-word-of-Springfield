# 🟡 Mining the Words of Springfield

A Text Mining project based on the dialogue lines of the iconic animated series *The Simpsons*, developed by Martina Pantò and Alessandro Bosi for the course **Text Mining and Search** (University of Milano-Bicocca, academic year 2024/2025).

## 📚 Project Description

This project analyzes over **60,000 dialogue lines** from more than **700 episodes** across the first 27 seasons of *The Simpsons*, aiming to explore:

- The linguistic style of main characters
- Recurring thematic structures
- Sentence tone and sentiment
- Narrative patterns and expressive anomalies

The analyses are implemented in two Google Colab notebooks covering preprocessing, vectorization, sentiment analysis, topic modeling, and clustering.

## 📂 Project Structure

- `TM_preprocessing_Bosi_Panto.ipynb`: dataset preprocessing, normalization, and linguistic feature extraction.
- `TM_tasks_code_Bosi_Panto.ipynb`: application of NLP and ML techniques to extract semantic and structural insights.
- `Simpson_TMeS_Panto_Bosi___twocolumns.pdf`: full project report.

## 🧪 Techniques Used

- **Preprocessing**: text cleaning, lemmatization, stopword removal, lexical analysis.
- **Text Representation**:
  - TF-IDF
  - Word2Vec (Skip-gram)
- **Topic Modeling**: Latent Dirichlet Allocation (LDA)
- **Clustering**:
  - K-Means
  - Agglomerative Clustering
- **Sentiment Analysis**:
  - Multinomial Naive Bayes
  - Random Forest
- **Visualization**:
  - WordClouds
  - PCA

## 📊 Key Results

- Characters show distinctive vocabulary: Lisa is introspective, Homer is impulsive.
- Clusters reveal narrative, humorous, and anomalous sentence types.
- Sentiment classifiers achieved an **accuracy of 81%**.

## 🗂 Dataset

- [The Simpsons Dataset (Abhinav Moudgil)](https://www.kaggle.com/datasets/abhinavmoudgil/the-simpsons-dataset)
- [Dialogue Lines Dataset (Pierre Megret)](https://www.kaggle.com/datasets/pierremegret/dialogue-lines-of-the-simpsons)

## ⚙️ Requirements

- Python ≥ 3.7
- Main libraries:
  - `pandas`, `numpy`, `nltk`, `gensim`, `scikit-learn`, `matplotlib`, `seaborn`, `wordcloud`

You can install them with:

```bash
pip install -r requirements.txt
```

> ⚠️ Notebooks are designed to run on **Google Colab**, where the environment is pre-configured.

## 🚀 Quick Start

1. Open both notebooks on Google Colab:
   - [TM_preprocessing](https://colab.research.google.com/drive/1ShEqSviu28WVFEwG6Y8A400IC879YJtp)
   - [TM_tasks](https://colab.research.google.com/drive/1W0ldaRNozqnjQ1eLtIl2fTr1zk3GHX0r)

2. Run `TM_preprocessing` first to obtain the cleaned dataset.

3. Proceed to `TM_tasks_code` for advanced text mining and ML analyses.

## 🔮 Future Work

- Neural embeddings (e.g., BERT)
- Sequence modeling (e.g., RNNs or Transformers)
- Fine-grained emotion classification
- Integration with non-verbal annotations or scene descriptions

## 👥 Authors

- Martina Pantò – `901346`
- Alessandro Bosi – `837381`

## 🏛 University

**University of Milano-Bicocca**  
Master’s Degree in *Data Science*  
Course: *Text Mining and Search* — Prof. Gabriella Pasi, Prof. Marco Viviani  
Academic Year: 2024/2025
