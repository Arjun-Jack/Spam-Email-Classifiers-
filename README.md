# 📧 Spam Email Classifier (ML + NLP Project)

A **Machine Learning based Spam Email Classification system** that accurately detects whether an email is **Spam** or **Not Spam** using **Natural Language Processing (NLP)** techniques.  
The model achieves **97.96% accuracy** and provides **confidence scores** for predictions.

---

## 🚀 Live Demo
🔗 https://safarwithak-spam-email-detector.streamlit.app/

---

## 📌 Features

- ✅ Spam / Not Spam detection  
- 📊 Model confidence (probability score)  
- 🌙 Dark & Light mode toggle  
- 📝 Email word count & character count  
- ⚡ Fast prediction using TF-IDF  
- 🎯 High accuracy (97.96%)  
- ☁️ Deployed on Streamlit Cloud  

---

## 🛠 Tech Stack

- **Python**
- **Streamlit**
- **NLTK**
- **Scikit-learn**
- **TF-IDF Vectorizer**
- **Multinomial Naive Bayes**
- **Pickle**

---

## 🧠 Machine Learning Workflow

1. Data Cleaning & Preprocessing  
2. Tokenization & Stopword Removal  
3. Stemming using Porter Stemmer  
4. Feature Extraction using TF-IDF  
5. Model Training (MultinomialNB)  
6. Model Evaluation & Accuracy Testing  
7. Deployment with Streamlit  

---

## 📂 Project Structure

```text
spam-email-classifier/
│
├── app.py               # Streamlit application
├── model.pkl            # Trained ML model
├── vectorizer.pkl       # TF-IDF vectorizer
├── requirements.txt     # Dependencies
├── README.md            # Project documentation
└── .gitignore

⚙️ Installation & Run Locally
1️⃣ Clone the repository
git clone https://github.com/SafarwithAK/spam-email-classifier.git
cd spam-email-classifier

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run the app
streamlit run app.py

Developed a Machine Learning based Spam Email Classifier using NLP and TF-IDF achieving 97.96% accuracy. Implemented confidence scoring, dark/light UI, and deployed the application on Streamlit Cloud.

⭐ Future Enhancements

📩 Gmail API integration

🤖 Deep Learning models

📈 Confusion Matrix visualization

🌍 Multi-language support

🏁 License

This project is licensed under the MIT License.
Feel free to use and modify it.

