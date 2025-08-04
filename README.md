# Emotion Classification for User Feedback 🎯
This project is part of a growth hacking pipeline designed to classify user feedback by emotional tone and use it for dynamic user segmentation. By understanding users’ emotional expressions, we can tailor offers, messages, and experiences that truly resonate with each segment — turning raw feedback into real growth.

## 🔍 Goal
To classify user feedback into emotion categories (e.g., joy, sadness, anger, etc.), then use those classifications to segment users and optimize marketing actions accordingly.

## 🛠️ Models & Experiments
- **Classical NLP using CountVectorizer + Logistic Regression**: Achieved a strong baseline with 89% accuracy.

- **TensorFlow LSTM Model**: Introduced deep learning but encountered overfitting, likely due to class imbalance.

- **Text Classification from HuggingFace Transformers**: Final model achieved 90.72% accuracy, highlighting the power of transfer learning and contextual embeddings.

## 📦 Tools Used
- Python (pandas, numpy)
- Scikit-learn
- TensorFlow/Keras
- HuggingFace Transformers
- Jupyter Notebooks for EDA & experiments


