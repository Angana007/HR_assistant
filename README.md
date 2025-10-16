# 🤖 AI HR Assistant – Intelligent Policy Query Automation using GPT  
### Making HR information instant, accurate, and accessible  

An intelligent assistant that automates employee HR policy queries using **OpenAI GPT-3.5**, **LangChain**, and **Gradio**.  
The chatbot reads HR documents (e.g., PDFs) and answers employee questions in **natural language (text or voice)** — improving response speed and reducing manual HR workload.

---

## 🎯 Project Overview  
Traditional HR departments spend significant time handling repetitive employee questions about leave policies, reimbursements, and benefits.  
This chatbot automates that process — employees can upload policy documents, ask questions conversationally, and receive accurate, contextual answers.  

✅ Built for **Nestlé’s HR policy document** as a case study  
✅ Demonstrates **document retrieval**, **semantic search**, and **Q&A chain** design  
✅ Features **text & voice interface** for accessibility  

---

## 🧠 How It Works  
1. **PDF Extraction:** HR documents are parsed with PyPDF2  
2. **Chunking & Embedding:** Text is split and converted to OpenAI vector embeddings  
3. **Semantic Search:** ChromaDB retrieves the most relevant context for each query  
4. **Response Generation:** GPT-3.5 generates a precise answer using the retrieved context  
5. **Interactive Interface:** Gradio provides text + voice chat functionality  

---

## 🚀 Features  

| Capability | Description |
|-------------|-------------|
| 📄 **PDF Upload** | Upload any HR policy document |
| 🔍 **Semantic Q&A** | Ask HR questions in plain English |
| 🧠 **Vector Search (LangChain + ChromaDB)** | Context-aware retrieval for accurate answers |
| 🗣️ **Voice Interaction** | Speak your question and hear the bot’s response |
| 💬 **Custom Prompt Template** | Context-guided responses aligned with company tone |
| 🌐 **Interactive UI (Gradio)** | Minimal, responsive interface |
| ☁️ **Deployable Prototype** | Works seamlessly on Google Colab or Hugging Face Spaces |

---

## 💡 Business Impact (Simulated Metrics)

| Impact Area | Outcome |
|--------------|----------|
| 🕒 Query Response Time | Reduced from minutes to seconds |
| 👥 HR Workload | Automated ~70% of repetitive employee queries |
| 📈 Productivity | Freed HR time for strategic work |
| 🌍 Accessibility | Enables multilingual and voice-friendly use cases |

---

## 🛠️ Tech Stack  

- **OpenAI GPT-3.5 Turbo** – Response generation  
- **LangChain** – Document parsing and Q&A chain  
- **ChromaDB** – Vector storage and retrieval  
- **PyPDF2 / pypdf** – PDF text extraction  
- **Gradio** – Web interface with text & voice  
- **gTTS** – Text-to-speech conversion  

---

## 🧩 Future Enhancements  

- 🔁 **Query Analytics Dashboard:** Track most common employee questions to help HR teams improve documentation  
- 🌍 **Multi-Language Support:** Enable employees across regions to query in their preferred language  
- 🧠 **Feedback Loop:** Collect user feedback to fine-tune the model and improve accuracy  
- 🔐 **Integration with HRMS:** Connect with HR systems for personalized responses  
- 📊 **Knowledge Summaries:** Generate department-wise or policy summaries  

---

## 👩‍💻 Author
**Angana Chakraborty**  
AI/ML Engineer | Data Analyst | Researcher  

📍 Kolkata, India  
🔗 [LinkedIn](https://linkedin.com/in/angana-chakraborty) • [GitHub](https://github.com/Angana007)

---
