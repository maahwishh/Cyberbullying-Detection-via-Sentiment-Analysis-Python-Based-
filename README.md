# Cyberbullying Detection via Sentiment Analysis Python Based
Cyberbullying detection model designed to analyze uploaded textual data and identify instances of harmful behavior, including racism, sexism, and general toxicity. This project implements Natural Language Processing (NLP) techniques and machine learning models to detect instances of cyberbullying on social media. It processes textual data, applies sentiment classification, and builds a predictive model to identify harmful content.

**🚀 Project Overview**<br>
**Objective:** Automatically detect cyberbullying in social media text using machine learning.<br>
**Dataset:** Customer reviews and social media comments containing special characters, numbers, emojis.<br>
**Approach:<br>**
Data Preprocessing: Cleaning text (stopword removal, stemming, tokenization).<br>
Feature Engineering: TF-IDF, word embeddings, sentiment scores.<br>
Model Training: Implementing Naïve Bayes, Logistic Regression, and Neural Networks.<br>
Evaluation: Measuring accuracy, precision, recall, and F1-score.<br>

🔧 Installation & Requirements

**1️⃣ Setup Environment**

pip install -r requirements.txt

**2️⃣ Required Libraries**

1. pandas – Data handling
2. numpy – Numerical operations
3. nltk – Text preprocessing
4. scikit-learn – Machine learning models
5. tensorflow/keras – Neural network training

**📊 Dataset & Preprocessing**

1. Text Cleaning: Removing special characters, numbers, and emojis.
2. Tokenization: Splitting text into words.
3. Vectorization: TF-IDF and word embeddings for feature extraction.
   
**🤖 Model Training**

We trained and tested multiple models to classify text as cyberbullying or non-cyberbullying:<br>
✅ Naïve Bayes – Fast and efficient for text classification<br>
✅ Logistic Regression – Baseline model with good interpretability<br>
✅ Random Forest – Better handling of imbalanced data<br>
✅ LSTM Neural Network – Deep learning model for better accuracy<br>

**📈 Evaluation**<BR>
Accuracy, Precision, Recall, F1-score<br>
Confusion Matrix & ROC Curve<br>

**📌 Next Steps**<br>
1. Fine-tuning deep learning models (LSTMs, Transformers).
2. Expanding dataset for better generalization.
3. Deploying as an API for real-time cyberbullying detection.
   
**🤝 Contributing**<br>
Feel free to fork this repository and create pull requests!<br>
For issues and suggestions, open a discussion.<br>

**📜 License**<br>
This project is MIT Licensed – you can modify and use it freely.<br>
