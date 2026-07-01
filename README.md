# 🧠 Fake News AI Detector

A modern Machine Learning web application that predicts whether a given news article is **REAL** or **FAKE** using Natural Language Processing (NLP) and a trained Logistic Regression model.

Built with Python, Scikit-Learn, and Streamlit.

---

## 🚀 Features
- **Real-Time Classification**: Instantly analyzes any copied-and-pasted news article text.
- **Modern UI**: Styled with a dark glassmorphic design and micro-animations for an interactive user experience.
- **Accurate NLP Pipeline**: Employs a TF-IDF (Term Frequency-Inverse Document Frequency) vectorizer combined with a tuned classification model.

---

## 🛠️ Installation & Setup

### 1. Prerequisites
Make sure you have **Python 3.8+** installed on your system.

### 2. Set Up Virtual Environment (Recommended)
Open your terminal/command prompt in the project root directory and run:
```powershell
# Create virtual environment
python -m venv venv

# Activate virtual environment (Windows)
.\venv\Scripts\activate
```

### 3. Install Dependencies
```powershell
pip install -r requirements.txt
```

### 4. Run the Web App
Start the Streamlit development server:
```powershell
streamlit run app.py
```
This will open the app automatically in your default web browser (typically at `http://localhost:8501`).

---

## 📁 Project Structure
* `app.py` - Streamlit application frontend, styles, and prediction logic.
* `lr_model.jb` - Pre-trained Logistic Regression classification model.
* `vectorizer.jb` - Pre-trained TF-IDF vectorizer for text feature extraction.
* `requirements.txt` - Project package dependencies.
* `Fake.csv` & `True.csv` - Datasets used for training the model.

---

## 👤 Author
* **Developer**: Trisha Jana
* **GitHub**: [@21trishajana](https://github.com/21trishajana)
* **Email**: 21trisha2005@gmail.com
