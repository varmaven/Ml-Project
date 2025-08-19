# Ml-Project
📧 Spam Email Classifier (Machine Learning Project)

A machine learning project that classifies SMS/email messages as Spam or Ham (Not Spam) using TF-IDF Vectorization and Logistic Regression.

🚀 Features

Preprocesses text data with TF-IDF Vectorization

Classifies messages as Spam or Ham

Achieves 95%+ accuracy on the SMS Spam Collection Dataset

Can be extended to an interactive web app (Streamlit/Flask)

📂 Project Structure
spam-email-classifier/
│── data/
│   └── spam.csv              # Dataset (Kaggle SMS Spam Collection)
│
│── src/
│   └── spam_classifier.py    # Main Python code
│
│── README.md                 # Documentation
│── requirements.txt          # Dependencies

⚙️ Installation
# Clone the repository
git clone https://github.com/<your-username>/spam-email-classifier.git
cd spam-email-classifier

# Install dependencies
pip install -r requirements.txt

▶️ Usage
cd src
python spam_classifier.py

📊 Example Output
✅ Accuracy: 0.96

              precision    recall  f1-score   support
           0       0.97      0.98      0.97       965
           1       0.92      0.90      0.91       150

📜 Tech Stack

Python

Pandas

Scikit-learn

NumPy

🏆 Future Improvements

Add a web interface using Flask or Streamlit.

