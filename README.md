 # Real-World Sentiment Analysis with DistilBERT 🎭

A Natural Language Processing (NLP) project that fine-tunes a Transformer model to detect sentiment in text. 

## 🚀 The Challenge
Standard sentiment models often fail on:
1.  **Sarcasm & Context:** "Great, just what I needed" (said sarcastically).
2.  **Internet Slang:** Emojis like 💀 (skull) or 🔥 (fire) carry heavy meaning.
3.  **Messy Data:** HTML tags and uncleaned text from web scraping.

## 💡 The Solution
This project implements a **DistilBERT** model using TensorFlow/Keras.
* **Preprocessing:** Includes a custom `clean_text` pipeline that "Demojizes" emojis (converting 😭 to text) so the model can interpret them.
* **Model:** Uses Transfer Learning (DistilBERT) to achieve high accuracy with lower computational cost than full BERT.
* **Dataset:** Trained on the IMDB Movie Reviews dataset.

## 🛠 Tech Stack
* **Python**
* **TensorFlow / Keras**
* **Hugging Face Transformers**
* **Emoji Library**

## 📊 Results
* **Accuracy:** ~90% (on test set)
* **Inference:** Capable of handling mixed-media text (Text + Emojis).

## 💻 Usage
Open the notebook in Google Colab to run the training pipeline:
[Link to your Colab notebook here]
