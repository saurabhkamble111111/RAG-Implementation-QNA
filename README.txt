# .gitignore file for a Python project

# Byte-compiled / optimized / DLL files
__pycache__/
*.py[cod]
*$py.class

# Virtual environment
.venv/
venv/

# Jupyter Notebook checkpoints
.ipynb_checkpoints/

# Dataset files
data/
datasets/
*.csv
*.json
*.tsv

# Logs and temporary files
logs/
*.log

# Environment variables
.env

# README.md file for Knowledge Whisperer RAG project

# Knowledge Whisperer - RAG Chatbot

## Project Overview
This project implements a Retrieval-Augmented Generation (RAG) chatbot that allows users to upload PDF or TXT files and query the content. The chatbot retrieves relevant document sections and generates responses using an LLM.

## Features
- Accepts PDF/TXT file uploads
- Extracts and chunks content
- Embeds document data for efficient retrieval
- Uses FAISS/ChromaDB for vector storage
- Implements LangChain/LlamaIndex for retrieval
- Integrates with an LLM (OpenAI, Hugging Face, etc.)
- Provides a simple UI (CLI, Flask, or Streamlit)

## Setup Instructions
1. Clone the repository:
   ```sh
   git clone <repo-url>
   cd knowledge-whisperer-rag
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the application:
   ```sh
   python app.py  # or streamlit run app.py
   ```

## Future Enhancements
- Multi-turn conversation memory
- Confidence scoring for responses
- Citing document sources
- Dockerized deployment

## License
This project is open-source and available for further development.
