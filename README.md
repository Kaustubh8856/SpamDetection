# 📩 SMS Spam Detection

A Natural Language Processing (NLP) project that classifies SMS messages as **spam** or **ham (not spam)** using traditional machine learning algorithms. This project demonstrates the end-to-end pipeline of text preprocessing, feature extraction, model training, and evaluation.

---

## 🚀 Features

- 📄 Loads the SMS Spam Collection Dataset (publicly available)
- 🧹 Cleans and preprocesses raw text messages
- 🔠 Transforms text into numerical form using **TF-IDF vectorization**
- 🧠 Trains multiple classification models:
  - Multinomial Naive Bayes
  - Support Vector Machines (SVM)
  - Logistic Regression
  - Decision Trees
- 📊 Evaluates models using accuracy, precision, recall, F1-score, and confusion matrix
- 📈 Visualizes results for easy comparison

---

## 🧠 How It Works

1. **Data Loading & Exploration**
   - Loads the dataset into a Pandas DataFrame
   - Analyzes the distribution of spam vs. ham messages
   - Visualizes message lengths and word frequency distributions

2. **Text Preprocessing**
   - Converts text to lowercase
   - Removes punctuation and stopwords
   - Applies stemming using **NLTK’s PorterStemmer**

3. **Feature Extraction**
   - Converts cleaned text into vectors using **TF-IDF (Term Frequency–Inverse Document Frequency)** to capture important terms
   - Produces a sparse matrix representation for model input

4. **Model Training**
   - Trains multiple classification models using `Scikit-learn`
   - Compares model performances to select the best one
   - Handles class imbalance during training

5. **Evaluation**
   - Uses metrics like **accuracy**, **precision**, **recall**, and **F1-score**
   - Displays results using **confusion matrix** and classification report
   - Plots performance metrics and model comparisons

---

## 🛠️ Tech Stack

- **Language**: Python
- **Libraries**:
  - `Scikit-learn` – Model building and evaluation
  - `Pandas`, `NumPy` – Data manipulation
  - `NLTK` – Natural language text processing
  - `Matplotlib`, `Seaborn` – Visualization
  - `TF-IDF Vectorizer` – Feature extraction from text

---

## ✅ Results

- Achieved high accuracy and recall with **Multinomial Naive Bayes**
- Lightweight and fast-performing model suitable for deployment in real-time systems like SMS filtering apps or chatbots
- Demonstrates practical applications of machine learning in NLP
