# 📧 Email Spam Classifier

A Machine Learning-based **Email Spam Classifier** built using **Python, Scikit-learn, Streamlit, and Natural Language Processing (NLP)**. The application classifies email/SMS messages as **Spam** or **Not Spam (Ham)** using a **TF-IDF Vectorizer** and a **Multinomial Naive Bayes** model.

---

## 🚀 Features

- 📩 Detects whether an email or SMS is Spam or Not Spam.
- 📝 Performs text preprocessing using NLP techniques.
- 🔤 Removes stopwords, punctuation, and applies stemming.
- 📊 Converts text into numerical features using TF-IDF Vectorization.
- 🤖 Classifies messages using the Multinomial Naive Bayes algorithm.
- 🌐 Interactive and user-friendly interface built with Streamlit.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Streamlit
- Pickle

---

## 📂 Project Structure

```
Email-Spam-Classifier/
│── app.py
│── model.pkl
│── vectorizer.pkl
│── Email_spam_classifier.ipynb
│── requirements.txt
│── README.md
```

---

## 📖 Project Workflow

1. Load the SMS Spam dataset.
2. Clean and preprocess the text data.
3. Convert text to lowercase.
4. Tokenize the text.
5. Remove punctuation and stopwords.
6. Apply Porter Stemming.
7. Transform text using TF-IDF Vectorizer.
8. Train the Multinomial Naive Bayes model.
9. Save the trained model and vectorizer using Pickle.
10. Deploy the classifier using Streamlit.

---

## 🧹 Text Preprocessing

The application performs the following preprocessing steps before prediction:

- Convert text to lowercase
- Tokenize the sentence
- Remove non-alphanumeric characters
- Remove English stopwords
- Remove punctuation
- Apply Porter Stemming
- Convert processed words back into a sentence

---

## 🤖 Machine Learning Model

- **Vectorization:** TF-IDF Vectorizer
- **Classification Algorithm:** Multinomial Naive Bayes

The trained model and vectorizer are stored using Pickle and loaded into the Streamlit application for real-time predictions.

---

## 💻 Installation

### Clone the repository

```bash
git clone 
```

### Navigate to the project folder

```bash
cd Email-Spam-Classifier
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Download NLTK resources

```bash
python -m nltk.downloader punkt
python -m nltk.downloader punkt_tab
python -m nltk.downloader stopwords
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

or

```bash
python -m streamlit run app.py
```

---

## 📸 Demo

### Example 1

**Input**

```
Congratulations! You have won a FREE iPhone.
Click here to claim your prize now.
```

**Prediction**

```
Spam
```

---

### Example 2

**Input**

```
Hi, are we meeting tomorrow at 10 AM?
```

**Prediction**

```
Not Spam
```

---

## 📈 Future Improvements

- Add prediction confidence score.
- Compare multiple machine learning models.
- Integrate Deep Learning models such as LSTM or BERT.
- Deploy on Streamlit Community Cloud.
- Support email attachment analysis.

---

## 👨‍💻 Author

**Soni Jain**

- GitHub: https://github.com/SoniJain03
- LinkedIn: https://www.linkedin.com/in/soni-jain-65a556265/

---

⭐ If you found this project useful, don't forget to give it a **Star** on GitHub!
