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

## 🎯 Strategic Value (Why HR Needs This)

Traditional HR departments spend significant time handling repetitive employee questions about leave policies, reimbursements, and benefits. This project solves that problem directly by leveraging automation to streamline HR communication.

---

## 📊 Business Metrics

| Metric | Before Automation (Manual) | After Automation (AI Assistant) |
|--------|-----------------------------|---------------------------------|
| **Query Response Time** | Minutes (searching documents) | Seconds (instant retrieval) |
| **Policy Consistency** | Variable (relies on HR rep knowledge) | 100% Consistent (based only on verified policy source) |
| **HR Workload Reduction** | High (repetitive Q&A) | Automated ~70% of routine queries |
| **Audit Readiness** | Low (no tracking of common Qs) | High (Analytics pinpointing policy pain points) |

---

## ✅ Case Study

Built and tested against **Nestlé’s HR policy document**, validating the system’s ability to interpret and respond accurately based on structured and unstructured HR policy data.

---

## 💼 Recruiter Takeaway

Demonstrates real-world application of **advanced NLP** to deliver measurable improvements in HR operations through quantifiable efficiency and accuracy gains.

---

## 🧠 Technical Deep Dive: How It Works

This solution uses a **Retrieval-Augmented Generation (RAG)** architecture to ensure responses are grounded only in the verified policy source, reducing risks of hallucination or misinformation.

| Component | Functionality |
|------------|----------------|
| **PDF Extraction** | HR documents parsed using `pypdf` for structured text extraction. |
| **Chunking & Embedding** | Text divided into coherent chunks and encoded using OpenAI embeddings. |
| **Semantic Search** | `ChromaDB` retrieves top-ranked policy paragraphs relevant to the user’s query. |
| **Response Generation** | `GPT-3.5` crafts precise, conversational answers using the retrieved context. |
| **Interface** | `Gradio` powers an interactive text/voice interface accessible on web platforms. |

---

## 🚀 Key Features

| Capability | Description |
|-------------|--------------|
| 📄 **Document Agnostic** | Upload any HR policy (PDF) to generate a new knowledge base instantly. |
| 🔍 **Contextual Q&A** | Ask complex HR-related questions in natural, conversational English. |
| 🗣️ **Voice Interaction** | Voice input and audio output via `gTTS`, enhancing accessibility. |
| 📊 **Query Analytics (Planned)** | Track frequently asked questions to guide HR documentation updates. |
| 🌐 **Interactive UI** | Deploy quickly on platforms like **Hugging Face Spaces** with a responsive design. |

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
## App in Action

Screenshot of the Main Interface

<img width="1280" height="645" alt="Screenshot from 2025-10-16 12-39-29" src="https://github.com/user-attachments/assets/4cbf8821-fbde-4222-9d29-e0deadb63c69" />

<img width="1273" height="642" alt="Screenshot from 2025-10-16 12-41-06" src="https://github.com/user-attachments/assets/8aa37c0c-6cab-4ab4-8961-c5559d6c0c55" />

## 👩‍💻 Author
**Angana Chakraborty**  
AI/ML Engineer | Data Analyst | Researcher  

📍 Kolkata, India  
🔗 [LinkedIn](https://linkedin.com/in/angana-chakraborty) • [GitHub](https://github.com/Angana007)

---
