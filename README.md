This project aims to detect human emotions from text inputs using Natural Language Processing (NLP) techniques and a BERT-based transformer model. The model classifies emotions into 10 categories plus neutral, such as joy, anger, sadness, fear, love, surprise, disgust, optimism, pessimism, and neutral.

The project is trained on GoEmotions, a dataset developed by Google containing 58k human-annotated Reddit comments labeled with 27 emotion categories. To simplify the classification task, these were mapped to 10 broad emotions plus neutral. The model can analyze text inputs like “I love this movie!” or “I can’t go outside because of the rain” and predict the underlying emotion.

Key Features

     i) Emotion classification from user text input.
     ii) Mapped 27 GoEmotions labels → 10 core emotions + neutral.
     iii) Fine-tuned BERT-base (uncased) model using PyTorch.
     iv)Tokenization and preprocessing with Hugging Face Transformers.
     v) Real-time user interaction (terminal input/output).
    vi) Emoji-based visualization of detected emotions.
    vii) Supports saving and reloading model weights and tokenizer.
