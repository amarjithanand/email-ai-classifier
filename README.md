## 📧 Self-Learning Intelligent Email Classification Extension

## 🚀 Overview  
This project is a production-ready, AI-powered email classification system that integrates with Gmail to automatically organize emails into personalized user-defined categories.

Unlike traditional rule-based filters, the system uses a hybrid AI architecture combining semantic embeddings and intelligent fallback models.

---

## 🧠 Key Highlights  
- High-performance backend using FastAPI  
- Hybrid AI (BERT + LLM fallback)  
- Self-learning with user feedback  
- Real-time Gmail integration  
- Smart confirmation system  

---

## 🏗️ Architecture  

Gmail API → FastAPI → BERT → Confidence Check → LLM → Decision → Gmail Labels

---

## ⚙️ Tech Stack  
- FastAPI  
- BERT (Sentence Transformers)  
- LLM (OpenAI API)  
- Gmail API  
- MongoDB  

---

## 🔧 Setup  

```bash
git clone https://github.com/amarjithanand/email-ai-classifier.git
cd email-ai-classifier
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```

---

## 📊 Workflow  
1. User labels emails  
2. Model learns patterns  
3. Classifies new emails  
4. Uses LLM if uncertain  
5. Learns from feedback  

---

## 🔐 Security  
- OAuth 2.0  
- Secure API access  
- Minimal permissions  

---

## ⭐ Conclusion  
A self-learning AI assistant for smart email management.
