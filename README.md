# RagBot
A Retrieval-Augmented Generation (RAG) bot built with LangChain, HuggingFace and FAISS.   It indexes your documents and allows you to chat with them through a Streamlit interface.

##  Features
- FAISS vector store
- HuggingFace LLM endpoint (e.g. Mistral 7B)
- Streamlit front‑end with chat interface
- Google Drive/Colab integration (optional)

##  Installation
```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
pip install -r requirements.txt

## Run

streamlit run rag_app.py

