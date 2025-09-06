# AI-Research-Agent

## Overview
An autonomous AI research assistant that leverages LLaMA (via Groq) to perform iterative literature review on arXiv papers. It searches, selects, downloads, summarizes papers, and suggests new research topics for continuous exploration.

## Features
* ArXiv Paper Search – Automatically queries arXiv for papers based on a search term.
* Paper Selection – Uses LLaMA to identify the most promising paper from search results.
* PDF Download & Text Extraction – Extracts metadata or full content from papers.
* Chunked Summarization – Splits large texts into manageable chunks and summarizes using Groq LLaMA.
* Automated Iteration – Generates a new research topic after each paper for continuous exploration.
* Error Handling – Skips empty chunks, retries API calls, and ensures robust execution

## Setup
1. **Clone repository**
```bash
git clone https://github.com/<username>/LLaMA-Research-Assistant.git
cd LLaMA-Research-Assistant
```

3. **Create virtual environment**
'''bash
python -m venv venv
venv\Scripts\activate     # Windows
'''

4. **Install dependencies**
'''bash
pip install -r requirements.txt
'''


5. **Set up environment variables**
'''bash
set GROQ_API_KEY="your_groq_api_key"
'''

6. **Run**
'''bash
python main.py
'''
