# 📧 Spam and Non-Spam Email Classification using Machine Learning

🔍 Overview
This project focuses on building and evaluating multiple machine learning models to classify emails as spam or not spam using the Spam Assassin Dataset. It leverages state-of-the-art preprocessing techniques like TF-IDF vectorization and compares the performance of three popular classifiers:

Logistic Regression
Multinomial Naive Bayes
Random Forest Classifier

📂 Dataset Details
The dataset was downloaded using the kagglehub library from Kaggle and contains preprocessed spam and non-spam email data.
text: The email body.
target: Label (0 = Not Spam, 1 = Spam).
The dataset combines multiple subsets from the SpamAssassin public corpus, excluding hard_ham and non-UTF-8 entries.

✅ Project Objectives
1. Load and clean the spam dataset.
2. Preprocess text using TF-IDF vectorization.
3. Train multiple ML models to classify emails.
4. Evaluate models using accuracy, precision, recall, and F1-score.

🧪 Models Trained
Model	Description
Logistic Regression	Linear model, robust with high-dimensional sparse input.
Multinomial NB	Ideal for text classification with word frequency input.
Random Forest	Ensemble model, reduces overfitting and boosts accuracy.

🛠️ Technologies Used
Python 
scikit-learn
pandas
numpy
kagglehub
TfidfVectorizer

📈 Evaluation Metrics
Each model is evaluated using:
Accuracy
Precision
Recall
F1-score
These metrics are printed using classification_report for both Spam and Not Spam classes.
