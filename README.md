# AI Research Co-Pilot

AI Research Co-Pilot is a smart research assistant that allows users to upload academic PDFs and ask natural language questions.  
It uses a Retrieval-Augmented Generation (RAG) pipeline built with Hugging Face Transformers, LangChain, and FAISS to provide accurate, context-aware answers.

---

## Features

- Upload and parse academic research papers (PDF)
- Semantic search using SentenceTransformers and FAISS
- Answer generation using Hugging Face language models
- Context-aware Q&A using LangChain
- Web-based interface with Gradio
- Custom logic for extracting authors and metadata for citation support

---

## Tech Stack

| Component              | Tools and Libraries                                 |
|------------------------|-----------------------------------------------------|
| Language Model         | Hugging Face Transformers, SentenceTransformers     |
| Vector Database        | FAISS                                               |
| Pipeline Orchestration | LangChain                                           |
| PDF Handling           | PyPDF2                                              |
| Interface              | Gradio                                              |
| Language               | Python                                              |

---

## How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/sreeya336/ai-research-co-pilot.git
   cd ai-research-co-pilot

## Example Use

Sample questions you can ask after uploading a PDF:

- Who are the authors of this paper?
- What architecture does the model use?
- What are the key findings or contributions?


