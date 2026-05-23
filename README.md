# 📄 AI-Powered PDF Question Answering System

A professional Retrieval-Augmented Generation (RAG) application that enables users to upload PDF documents and interact with them through natural language queries. The system leverages advanced Large Language Models (LLMs), semantic search, and vector embeddings to generate accurate, context-aware responses from uploaded documents.
<img width="1413" height="331" alt="image" src="https://github.com/user-attachments/assets/a892217f-6400-49de-aed7-73e557e0c528" />



---

#  Overview

This project combines the power of:

- **LangChain** for orchestration
- **Groq LLMs** for ultra-fast inference
- **Hugging Face Embeddings** for semantic understanding
- **FAISS Vector Database** for efficient similarity search
- **Gradio** for an interactive web-based interface

The application processes PDF documents, converts them into vector embeddings, retrieves the most relevant content based on user queries, and generates intelligent answers grounded in the uploaded document.

<img width="1907" height="769" alt="image" src="https://github.com/user-attachments/assets/e17db78b-1f3c-41cb-be65-dbc16ca2dfb0" />

---

# ✨ Key Features

-  Upload and process PDF documents
-  AI-powered conversational interface
-  Semantic document retrieval using vector search
-  High-speed inference with Groq LLMs
-  Context-aware question answering
-  Deployable on Hugging Face Spaces
-  Retrieval-Augmented Generation (RAG) architecture
-  User-friendly Gradio interface

---

#  System Architecture

```text
PDF Document
      │
      ▼
Document Loader (PyPDFLoader)
      │
      ▼
Text Splitting
      │
      ▼
Hugging Face Embeddings
      │
      ▼
FAISS Vector Store
      │
      ▼
Retriever
      │
      ▼
Groq LLM
      │
      ▼
Generated Response
```

---

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core Programming Language |
| LangChain | LLM Application Framework |
| Groq API | Large Language Model Inference |
| Hugging Face | Sentence Embeddings |
| FAISS | Vector Similarity Search |
| Gradio | Web Application Interface |
| PyPDF | PDF Processing |

---

# 📂 Project Structure
```bash
├── app.py
├── requirements.txt
├── README.md
```

---

# ⚙️ Installation

## Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🔑 Environment Configuration

Create a `.env` file or configure your secret variables inside Hugging Face Spaces.

```env
GROQ_API_KEY=your_groq_api_key
```

---

# ▶️ Running the Application

```bash
python app.py
```

The application will launch locally using Gradio.

---

# 🌐 Hugging Face Spaces Deployment

This project is fully compatible with Hugging Face Spaces.

### Required Files

- `app.py`
- `requirements.txt`
- `README.md`

### Add Repository Secret

Navigate to:

```text
Settings → Repository Secrets
```

Add the following secret:

| Name | Value |
|---|---|
| GROQ_API_KEY | Your Groq API Key |

---

# 💡 Example Use Cases

- Resume/CV analysis
- Academic paper question answering
- Legal document exploration
- Research summarization
- Business report analysis
- Intelligent document search

---

#  Application Preview

Users can upload PDF documents and ask context-aware questions directly through the web interface.


---

# 📈 Future Improvements

- Multi-document support
- Chat history memory
- Streaming responses
- OCR for scanned PDFs
- Citation-based answers
- Advanced reranking pipelines

---

# 👩‍💻 Author

**Maram Moustafa**



