Task-2
google colab link: https://colab.research.google.com/drive/1vu4KQWanVjVCUzAgRk9H4AWVtULZo7mz?usp=sharing
## Overview
This project implements a Retrieval-Augmented Generation (RAG) pipeline using Scrapy for web scraping, Sentence Transformers for embedding text, FAISS for similarity search, and OpenAI's API for generating responses. The goal is to extract text data from university websites, chunk and embed the data, store it for efficient retrieval, and generate responses to user queries.

## System Requirements
### Hardware Requirements
- CPU: Multi-core processor
- RAM: Minimum 8GB
- Storage: Sufficient space to store scraped data and embeddings

### Software Requirements
- Operating System: Windows, macOS, or Linux
- Python: Version 3.6 or above

### Dependencies
- `scrapy`
- `sentence-transformers`
- `numpy`
- `faiss-cpu`
- `openai`
- `json`
- `os`

You can install these dependencies using pip:
```bash
pip install scrapy sentence-transformers numpy faiss-cpu openai
