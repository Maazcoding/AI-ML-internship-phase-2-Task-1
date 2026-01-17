RAG Chatbot with Memory
A modular Retrieval-Augmented Generation (RAG) system built in Google Colab. This chatbot can retrieve information from custom documents and remember previous parts of the conversation.

🚀 Execution Flow
Run the notebook cells in order:

Setup: Install dependencies and configure API keys.

Environment: Initialize folders and write modular scripts (config.py, rag_engine.py, app.py).

Data: Generate sample data and initialize the vector database.

Launch: Test the engine and deploy the UI via ngrok.

🛠️ Project Structure
rag_engine.py: Handles document embeddings, retrieval, and conversation memory.

app.py: The web-based chat interface.

config.py: Centralized settings and parameters.

/data: Storage for your source documents.

🧰 Tech Stack
Framework: LangChain

Vector DB: ChromaDB

UI: Streamlit / Gradio

Tunneling: CLOUDFLARE

