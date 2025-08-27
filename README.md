# 📧 Spam Mail Prediction using Logistic Regression

This project classifies emails as **Spam** or **Not Spam (Ham)** using **Logistic Regression**, a simple yet powerful machine learning algorithm for binary classification.  
The model is trained on a dataset of labeled emails and uses text processing (Bag of Words / TF-IDF) to convert email text into numerical features for training.

---

## 📊 Dataset
- **Source**: Spam Email dataset (commonly available from UCI / Kaggle)  
- **Features**: Email text (after preprocessing)  
- **Target**:
  - `0` → Ham (Not Spam)  
  - `1` → Spam  

---

## ⚙️ Technologies Used
- Python 🐍  
- NumPy  
- Pandas  
- Scikit-learn  

---

## 🚀 How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/spam-mail-prediction.git
```
2️⃣ Install the requirements
```
pip install -r requirements.txt
```
3️⃣ Run the notebook
```
jupyter notebook spam_mail_prediction.ipynb
```
📈 Results

Model: Logistic Regression

Accuracy achieved: ~96% (on test data)

Preprocessing: Lowercasing, removing punctuation, tokenization, TF-IDF feature extraction

🔮 Future Improvements

Use advanced models (Naive Bayes, Random Forest, XGBoost, Deep Learning)

Add more preprocessing (stopword removal, lemmatization)

Build a web app with Streamlit/Flask for real-time email spam detection

🌐 Connect with Me
https://www.linkedin.com/in/harsh-pandey-891261354/

Or run directly in Google Colab.-mail-prediction
