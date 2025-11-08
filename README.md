# 💬 Emotion Detection using BERT (NLP-Based Approach)

Detects human emotions such as joy, anger, sadness, fear, and more from text using NLP and BERT.

---

## 🚀 Overview
This project fine-tunes a **BERT (base, uncased)** model using the **GoEmotions dataset** by Google to classify text into **10 emotions + neutral**. It can interpret sentences and predict their emotional tone, suitable for chatbots, social media analytics, and AI-based communication systems.

---

## 🧠 Features
- Detects 10 emotions + neutral from text.
- Uses **GoEmotions** dataset with 43k+ training samples.
- Fine-tuned **BERT-base** model with PyTorch and Transformers.
- Real-time text emotion prediction (terminal-based).
- Emoji representation for predicted emotions.
- Saves model and tokenizer for reuse.

---

## 🧩 Emotion Classes

## ⚙️ Tech Stack
- **Language:** Python  
- **Libraries:** PyTorch, Transformers, Pandas, Scikit-learn, NumPy  
- **Model:** BERT (bert-base-uncased)  
- **Dataset:** [GoEmotions](https://github.com/google-research/google-research/tree/master/goemotions)  
- **Platform:** Google Colab  
