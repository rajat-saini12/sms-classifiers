# email-spam-classifier-new
# 📧 Email/SMS Spam Classifier

This project is a machine learning-based web application that classifies messages as **spam** or **not spam** (ham) using natural language processing (NLP). Built with **Python**, **Streamlit**, and **scikit-learn**, it uses an intuitive interface to make predictions on user-input messages.

---

## 🚀 Demo

Launch the app locally:
```bash
streamlit run app.py

## project structure
sms-spam-classifier/
│
├── app.py                   # Streamlit app script
├── model.pkl                # Trained model file
├── vectorizer.pkl           # TF-IDF vectorizer
├── README.md                # Project documentation
└── requirements.txt         # Python dependencies

#  🧠 Model Information
Text Preprocessing:

Lowercasing

Removing special characters and punctuation

Stopword removal (using NLTK)

Lemmatization

Vectorization: TF-IDF Vectorizer

Classifier: Naive Bayes / Logistic Regression (customizable)

 # 🛠️ Installation
1.Clone the repository:
2. Install dependencies:
3. Download required NLTK data:
        import nltk
        nltk.download('stopwords')
        nltk.download('punkt')
        nltk.download('wordnet')
        nltk.download('omw-1.4')
4. how to use 
       streamlit run app.py
