# personality_prediction
This project uses AI/ML and Generative AI techniques to predict a person’s MBTI Personality Type based on their social media posts.

📌 Features

Data preprocessing (cleaning text, removing stopwords, links, and punctuation)
Feature extraction using TF-IDF Vectorization
Personality prediction using Logistic Regression
Pre-trained model saved with Joblib for future predictions
Easy-to-use prediction function

📂 Dataset

We use the MBTI Personality Types Dataset
 from Kaggle.
The dataset (mbti_1.csv) contains:
type: Personality type (e.g., INFJ, ENTP, INTP)
posts: Social media posts by the user

Example Results

Accuracy: ~60-65% (varies depending on dataset split)
Model: Logistic Regression
Feature Extraction: TF-IDF

📌 Requirements

Python 3.7+
pandas
scikit-learn
nltk
joblib
(Already included in requirements.txt)

📜 Future Improvements

Try Deep Learning models (BERT, LSTMs) for higher accuracy
Add web app (Flask/Streamlit) for interactive personality prediction
Generate personality insights using Generative AI
