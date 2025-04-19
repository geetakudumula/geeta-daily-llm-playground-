# 💬 Real-time Sentiment Analyzer (Streamlit + Hugging Face)

A real-time, interactive sentiment analysis web app built using **Streamlit** and **Hugging Face Transformers**. This app allows users to enter custom sentences and instantly get back a prediction of the sentence's **sentiment** — either **POSITIVE** or **NEGATIVE** — along with a confidence score.

> ⚡ Powered by `distilbert-base-uncased-finetuned-sst-2-english`  
> 👩‍💻 Created by **Geeta Kudumula**, Technical AI/ML Architect

---

## 🚀 Demo

![Demo Screenshot](https://github.com/geetakudumula/geeta-daily-llm-playground-/blob/main/DemoScreenshot.png?raw=true)

Try typing in:
- `The service was excellent and fast!`
- `This product made things worse.`
- `It's okay, not the best but not the worst.`

---

## 🧠 Under the Hood

- **Model:** `distilbert-base-uncased-finetuned-sst-2-english` (from Hugging Face)
- **Framework:** Python with [Streamlit](https://streamlit.io/) for front-end
- **Libraries:** `transformers`, `torch`, `streamlit`

---

## 🖥️ How to Run This Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/geetakudumula/realtime-sentiment-analyzer-streamlit.git
   cd realtime-sentiment-analyzer-streamlit
