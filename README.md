# LangChain Web & Document Loaders (`LLM-web`)

![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-Document_Loaders-1C3C3C?logo=langchain&logoColor=white)
![NLTK](https://img.shields.io/badge/NLP-NLTK-2E7D32)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)

Hands-on **LangChain Document Ingestion & Web Scraping** workflows for Retrieval-Augmented Generation (RAG) pipelines, demonstrating how to ingest plain text, structured CSVs, and live news URLs into LangChain `Document` objects.

---

## Covered Workflows

1. **Plain Text Ingestion (`TextLoader`)**: Loading financial news articles (`nvda_news_1.txt`) with metadata extraction.
2. **Structured Tabular Ingestion (`CSVLoader`)**: Parsing movie records (`movies.csv`) with custom `source_column="title"` metadata attribution.
3. **Web Page Scraping (`WebBaseLoader` & `UnstructuredURLLoader`)**: Fetching and parsing live financial news articles and web pages into clean text segments.
4. **NLTK Tokenization (`punkt`)**: Sentence and word tokenization setup for downstream text splitting and chunking.

---

## Project Structure

```text
LLM-web/
├── langchain_document_loaders.ipynb  # Jupyter Notebook demonstrating LangChain loaders & NLTK
├── movies.csv                        # Sample tabular dataset for CSVLoader
├── nvda_news_1.txt                   # Sample NVIDIA financial news article for TextLoader
└── requirements.txt                  # Python package dependencies
```

---

## Getting Started

```bash
git clone https://github.com/ysri10/LLM-web.git
cd LLM-web
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook langchain_document_loaders.ipynb
```
