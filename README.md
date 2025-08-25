# 📩 Email & SMS Spam Classifier

A machine learning web application built with **Streamlit**, **scikit-learn**, and **NLTK** that classifies Email/SMS messages as **Spam** or **Not Spam**.

---

## 🚀 Features
- 🔍 Classify text messages into **Spam** or **Ham** (Not Spam)
- 🧠 Uses a trained machine learning model (Multinomial Naive Bayes or Logistic Regression)
- 🧹 Preprocesses input using:
  - Lowercasing
  - Removing punctuation
  - Removing stopwords
  - Tokenization
  - Stemming (Porter Stemmer)
- 🎨 Interactive UI built using **Streamlit**
- 📦 Easily deployable to platforms like **Render**

---

## 🛠 Tech Stack
- **Frontend**: Streamlit
- **Machine Learning**: scikit-learn
- **Text Preprocessing**: NLTK
- **Data Handling**: NumPy, Pandas
- **Visualization (optional)**: Matplotlib

---

## 📂 Project Structure
📦 Email-SMS-Spam-Classifier
├── app.py # Main Streamlit app
├── vectorizer.pkl # Saved TF-IDF vectorizer
├── model.pkl # Trained ML model
├── spam.csv # Dataset used for training
├── requirements.txt # Dependencies
└── README.md # Project documentation

---

## 📊 Dataset
- Source: SMS Spam Collection Dataset  
- Labels:
  - **ham** → Not Spam  
  - **spam** → Spam  
- Preprocessing steps:
  - Lowercasing  
  - Removing punctuation & stopwords  
  - Tokenization  
  - Stemming with Porter Stemmer  
  - TF-IDF Vectorization  

---

## 🧪 Example Inputs

| Message                                                                 | Prediction |
|-------------------------------------------------------------------------|-------------|
| "I am free today, let's go out for a movie!"                            | ✅ Ham |
| "A loan for £950 is approved for you if you receive this SMS..."        | 🚫 Spam |
| "Did you see the match? It was insane"                                  | ✅ Ham |
| "Accident compensation: You have still not claimed the compensation..." | 🚫 Spam |
| "I love you... Do you love me?"                                         | ✅ Ham |

---

## ⚙️ Installation & Usage

### 1️⃣ Clone the repo
```bash
git clone https://github.com/your-username/Email-SMS-Spam-Classifier.git
cd Email-SMS-Spam-Classifier
```
### 2️⃣ Create virtual environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
```
### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```
### 4️⃣ Run the Streamlit app
```
streamlit run app.py
```
🌐 Deployment

Deployed on Render
Build Command:
```
pip install -r requirements.txt
```
Start Command:
```
streamlit run app.py --server.port $PORT --server.headless true
```

Live Demo 👉``` https://email-sms-spam-classifier-xyx6.onrender.com/```

👨‍💻 Author

Amrit Mohanty
📧 amritmohanty.five@gmail.com
🌐 GitHub: https://github.com/amritM03
📝 License
This project is licensed under the MIT License.


Would you like me to also add a **“Demo Screenshot” section** (with a placeholder image) so your GitHub README looks more professional and attractive?

