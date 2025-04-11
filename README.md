# 💬 Intent-Based Chatbot using NLP

An interactive chatbot built using **Natural Language Processing (NLP)** techniques for intent classification. It combines **TF-IDF**, **Sentence-BERT embeddings**, and a **Random Forest classifier** to deliver fast and accurate responses, wrapped in a **Streamlit web interface**.

---

## 🌟 Features

- 💡 Recognizes user intent using **TF-IDF** and **Sentence-BERT**  
- 🌲 Uses a **Random Forest classifier** for multi-intent prediction  
- 📈 Achieved up to **97% accuracy** on training data  
- ⚡ Fast response generation with **lightweight pipeline**  
- 🖥️ Deployed with a **Streamlit interface** for easy interaction

---

## 🧠 Model Overview

| Component        | Description                       |
|------------------|-----------------------------------|
| Embeddings       | Sentence-BERT + TF-IDF            |
| Classifier       | Random Forest                     |
| Interface        | Streamlit                         |
| Accuracy         | Up to 97%                         |
| Optimization     | 40% faster responses via JSON pipeline |

---

## 🗂️ Folder Structure

chatbot-nlp/ ├── data/ │ └── intents.json ├── models/ │ ├── tfidf_vectorizer.pkl │ ├── sentence_transformer.pkl │ └── rf_model.pkl ├── chatbot_app.py ├── preprocessing.py ├── train_model.py ├── requirements.txt └── README.md

yaml
Copy
Edit

---

## ⚙️ Getting Started

### 🔧 To Run Locally:

1. Clone the repository:
git clone https://github.com/Vikas717-creator/chatbot-nlp.git cd chatbot-nlp

markdown
Copy
Edit

2. Install dependencies:
pip install -r requirements.txt

markdown
Copy
Edit

3. Run the Streamlit app:
streamlit run chatbot_app.py

yaml
Copy
Edit

4. Chat with the bot at `http://localhost:8501/`

---

## 🧪 Example Interaction

> **User:** _"What is the tallest mountain"_  
> **Bot:** _"Mount Everest is the taleest mountain in the world."_  

> **User:** _"How to prepare for a speech?"_  
> **Bot:** _"Prepare for a speech by researching your topic and practicing in front of a mirror or with friends."_

---

## 📊 Technologies Used

- Python  
- Streamlit  
- Scikit-learn  
- Sentence-Transformers (BERT)  
- TF-IDF  
- Pandas / NumPy  

---

## 📈 Performance

| Metric     | Score |
|------------|-------|
| Accuracy   | 97%   |
| Response Time | Reduced by 40% (via optimized JSON flow) |

---

## 🔮 Future Enhancements

- 🧠 Switch to fine-tuned BERT or LLM (e.g., DistilBERT, RoBERTa)  
- 🗣️ Add text-to-speech and voice command support  
- 📊 Track and visualize chatbot analytics  
- 🌐 Deploy on Hugging Face Spaces or Streamlit Cloud

---

## 🤝 Contributing

Feel free to contribute! Fork the repository and create a pull request.

---
## 🔗 Connect with Me

- GitHub: [@Vikas717-creator](https://github.com/Vikas717-creator)  
- LinkedIn: [Vikas Thakur](https://www.linkedin.com/in/vikas-thakur-2304a6261/)
