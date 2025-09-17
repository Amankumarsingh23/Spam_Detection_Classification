📄 README.md
# 📨 Spam Comment Detection using Naive Bayes  

![Python](https://img.shields.io/badge/Python-3.9-blue.svg)  
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)  
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)  

## ✨ Project Overview  
This project is an **NLP-based Machine Learning model** that detects whether a YouTube comment is **Spam 🚫** or **Not Spam ✅**.  
It uses the **Naive Bayes Classifier (BernoulliNB)** with **CountVectorizer** to transform text into numerical features.  

---

## 📂 Dataset  
We used the **YouTube Spam Collection Dataset**, specifically `Youtube01-Psy.csv`.  
- **CONTENT** → YouTube comment text 💬  
- **CLASS** → Spam (1) / Not Spam (0)  

---

## ⚙️ Tech Stack  
- 🐍 **Python 3**  
- 📊 **Pandas, NumPy**  
- 🧠 **Scikit-learn (Naive Bayes, CountVectorizer, Train-Test Split)**  

---

## 🚀 How to Run  

1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/spam-comment-detection.git
   cd spam-comment-detection


Install dependencies

pip install -r requirements.txt


Run the script / notebook

python spam_detection.py

🔮 Example Prediction
sample = "hii llike share my post"
data = cv.transform([sample]).toarray()
print(model.predict(data))  
# Output → ['Spam']

📊 Results

Training Accuracy: ~95% ⚡

Fast and lightweight model (works well on small datasets).

🌟 Future Improvements

Use advanced models (Logistic Regression, SVM, Deep Learning)

Deploy as a Flask/Django Web App 🌐

Add support for multiple languages

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss.
