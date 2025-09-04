## 💬 Sentiment Analysis using NLP

This project applies Natural Language Processing (NLP) and machine learning techniques to classify customer reviews into positive or negative sentiments. It demonstrates a complete workflow from raw data preprocessing to model evaluation and visualization.

### 📂 Dataset
- A dataset of product/customer reviews (CSV format).
- Contains text data with sentiment labels (positive/negative).

### 🔍 Methodology
1. **Data Preprocessing**:
   - Removal of stopwords, punctuation, and special characters.
   - Tokenization and normalization of text.
   - Lemmatization for word reduction.
2. **Feature Engineering**:
   - TF-IDF vectorization to transform text into numerical features.
3. **Model Training**:
   - Logistic Regression classifier (primary model).
   - Comparison with Naive Bayes for baseline performance.
4. **Evaluation**:
   - Accuracy, precision, recall, F1-score.
   - Confusion matrix heatmap.
5. **Visualization**:
   - WordClouds of frequent positive/negative words.

### 🛠️ Tech Stack
- Python (Pandas, NumPy, Scikit-learn)
- NLTK for NLP preprocessing
- Matplotlib & Seaborn for visualization
- WordCloud for textual insights

### 🚀 How to Run
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Open and run the Jupyter notebook
4. Explore preprocessing, training, and evaluation outputs

