# 🤖 BERT Chatbot using Streamlit

A simple AI-powered chatbot built with **BERT (Bidirectional Encoder Representations from Transformers)** and **Streamlit**. The chatbot understands user queries using semantic similarity and returns the most relevant predefined response.

## 🚀 Features

- 🧠 Uses Google's BERT model for understanding user queries
- 💬 Semantic similarity matching using Cosine Similarity
- 🎨 Interactive Streamlit web interface
- ⚡ Fast response with cached BERT model
- 🤖 Predefined Question & Answer system
- 📚 Easy to customize by adding new questions and answers

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Hugging Face Transformers
- BERT (bert-base-uncased)
- PyTorch
- Scikit-learn
- NumPy

---

## 📂 Project Structure

```
bert-chatbot-streamlit/
│
├── bert_chatbot.py          # Main application
├── requirements.txt         # Required libraries
├── README.md                # Project documentation
└── background.jpg           # Background image (optional)
```

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/bert-chatbot-streamlit.git
```

### 2. Move into the project folder

```bash
cd bert-chatbot-streamlit
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run bert_chatbot.py
```

The application will open in your browser.

---

## 💬 Sample Questions

Try asking:

- What is your name?
- What is BERT?
- What is AI?
- What is Data Science?
- What is Microsoft Azure?
- Tell me a joke.
- How are you?

---

## ⚙️ How It Works

1. User enters a question.
2. The BERT model converts the input into embeddings.
3. Cosine similarity compares the embedding with predefined questions.
4. The chatbot returns the most similar answer.
5. If similarity is below the threshold, it returns:

```
I'm not sure how to respond to that.
```

---

## 📚 Dependencies

- streamlit
- transformers
- torch
- scikit-learn

Install using:

```bash
pip install streamlit transformers torch scikit-learn
```

---

## 📸 Application Preview



```


---

## 🔮 Future Improvements

- Connect with OpenAI or Gemini API
- Voice input support
- Chat history
- Multiple language support
- Database integration
- Fine-tuned BERT model
- PDF Question Answering
- RAG implementation

---

## 👩‍💻 Author

**Swati Jadhav**

AI & Data Science Student

GitHub: https://github.com/swati2064

LinkedIn: https://linkedin.com/in/swati-jadhav-b759a6315

