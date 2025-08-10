# 🧠 Mental Health Text Dataset & Model Experiments ✨

📦 **Curated dataset** of mental-health-related text scraped from public online sources (blogs, Q&A forums, motivational sites).  
🎯 Perfect for **research, NLP experiments & model training**—from vanilla RNNs to state-of-the-art transformers.

---

## 📂 Dataset at a Glance

| Field        | Details |
|--------------|---------|
| 📰 **Sources** | Public blogs, Q&A forums, motivational sites |
| 🧩 **Topics** | Depression, anxiety, self-improvement, happiness, motivation, suicidal thoughts |
| 📄 **Format** | JSON |

---

## ⚙️ Data Pipeline: From Raw to Ready

1. 🕷️ **Scraping**  
   Google + BeautifulSoup + Selenium (auto-scroll for Quora).

2. 🧹 **Cleaning**  
   Strip HTML tags, stopwords, special characters.

3. 🔤 **Tokenization**  
   • Transformers: WordPiece / BERT tokenizer  
   • RNNs: Keras tokenizer

4. ✂️ **Padding / Truncation**  
   Uniform sequence lengths across the board.

---

## 🧪 Model Zoo (notebooks included)

| Model | Emoji |
|-------|-------|
| **Simple RNN** | ⏳ |
| **LSTM** | 🧠 |
| **GRU** | ⚙️ |
| **BiLSTM** | ↔️🧠 |
| **Transformers (BERT, RoBERTa, etc.)** | 🤖 |

---
