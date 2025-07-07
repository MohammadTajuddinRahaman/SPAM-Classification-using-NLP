# SPAM-Classification-using-NLP
Before NLP spam classification, you need to convert the text using BOW and TFIDF.
📧 Spam Classification Using NLP
This project implements a Spam Detection System using Natural Language Processing (NLP) and various Machine Learning classifiers. The goal is to classify SMS messages as either "spam" or "ham" (not spam) using text preprocessing, feature extraction, and supervised learning algorithms.

🔍 Overview
Input: SMS message dataset with labeled data (spam or ham)

Techniques Used:

Text cleaning and preprocessing

Tokenization and stopword removal

TF-IDF Vectorization

Machine Learning Models: Multinomial Naive Bayes, SVM, KNN, etc.

Evaluation using Accuracy, Confusion Matrix, and a Bar Graph comparison
🧠 Models Compared
Model	                        Accuracy	F1-Score	Precision  	Recall
Naive Bayes        	                ✅	  ✅	      ✅	        ✅
Support Vector Machine	            ✅	  ✅	      ✅        	✅
K-Nearest Neighbors	                ✅	  ✅	      ✅        	✅

📊 Output
Word clouds of spam/ham texts

TF-IDF features

Model accuracy bar graph

Confusion matrices for evaluation

📚 Future Work
Use Deep Learning (e.g., LSTM)

Implement real-time SMS classifier

Add deployment with Flask/Streamlit
