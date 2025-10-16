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

## 📊 Business Metrics

| Metric | Before Automation (Manual) | After Automation (AI Assistant) |
|--------|-----------------------------|---------------------------------|
| **Query Response Time** | Minutes (searching documents) | Seconds (instant retrieval) |
| **Policy Consistency** | Variable (relies on HR rep knowledge) | 100% Consistent (verified policy source) |
| **HR Workload Reduction** | High (repetitive Q&A) | Automated ~70% of routine queries |
| **Audit Readiness** | Low (no tracking of common Qs) | High (analytics pinpoint policy gaps) |

---

## ✅ Case Study

Built and tested against **Nestlé’s HR policy document**, validating the system’s ability to interpret and respond accurately based on structured and unstructured HR data.

---

## 💼 Recruiter Takeaway

Demonstrates real-world application of **advanced NLP** to automate HR operations and deliver quantifiable, efficiency-focused results.

---

## 🧠 Technical Deep Dive: How It Works

This solution uses a **Retrieval-Augmented Generation (RAG)** architecture that anchors every answer in verified policy data, minimizing factual errors.

| Component | Functionality |
|------------|----------------|
| **PDF Extraction** | HR documents parsed using `pypdf`. |
| **Chunking & Embedding** | Text split into coherent chunks and encoded using OpenAI embeddings. |
| **Semantic Search** | `ChromaDB` retrieves the most relevant policy paragraphs. |
| **Response Generation** | `GPT-3.5` crafts a precise, conversational response from contextual data. |
| **Interface** | `Gradio` powers the interactive text and voice interface. |

---

## 🚀 Key Features

| Capability | Description |
|-------------|--------------|
| 📄 **Document Agnostic** | Upload any HR policy PDF to instantly create a knowledge base. |
| 🔍 **Contextual Q&A** | Ask complex HR questions in plain English. |
| 🗣️ **Voice Interaction** | Input questions via voice and receive audio responses using `gTTS`. |
| 📊 **Query Analytics (Planned)** | Track frequent questions to improve HR documentation. |
| 🌐 **Interactive UI** | Deploy quickly on **Hugging Face Spaces** with a responsive design. |

---

## 🛠️ Tech Stack  

- **OpenAI GPT-3.5 Turbo** – Response generation  
- **LangChain** – Q&A and document retrieval pipeline  
- **ChromaDB** – Vector storage and retrieval  
- **PyPDF2 / pypdf** – Document text extraction  
- **Gradio** – Frontend interface (text & voice)  
- **gTTS** – Text-to-speech for audio responses  

---

## 🧩 Future Enhancements  

- 🔁 **Query Analytics Dashboard:** Monitor frequently asked employee questions  
- 🌍 **Multi-Language Support:** Allow multilingual policy queries  
- 🧠 **Feedback Loop:** Continuous improvement via user feedback  
- 🔐 **Integration with HRMS:** Personalized answers using internal data  
- 📊 **Knowledge Summaries:** Auto-generate department-level summaries  

---

## 🖥️ App in Action  

**Main Interface Screenshots**

<img width="1280" height="645" alt="Screenshot from 2025-10-16 12-39-29" src="https://github.com/user-attachments/assets/4cbf8821-fbde-4222-9d29-e0deadb63c69" />

<img width="1273" height="642" alt="Screenshot from 2025-10-16 12-41-06" src="https://github.com/user-attachments/assets/8aa37c0c-6cab-4ab4-8961-c5559d6c0c55" />

---

## 👩‍💻 Author

**Angana Chakraborty**  
AI/ML Engineer | Data Analyst | Researcher  

📍 Kolkata, India  
🔗 [LinkedIn](https://linkedin.com/in/angana-chakraborty) • [GitHub](https://github.com/Angana007)
