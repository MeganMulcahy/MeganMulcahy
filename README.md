# Hey, I'm Megan 👋

CS grad + MBA candidate at the University of Alabama. I build AI systems — 
mostly RAG pipelines, LLM applications, and the tooling around them. 
Relocating to Dallas and targeting AI Engineer roles.

---

## What I work with

**AI / ML**
Python · LlamaIndex · LangChain · Gemini · Claude API · Whisper · 
sentence-transformers · BM25 · cross-encoder reranking · RAGAs · 
PyMuPDF · pytesseract · ChromaDB · vector search

**Backend & Infra**
FastAPI · Supabase · Railway · PostgreSQL · REST APIs · Google Cloud Platform

**Frontend**
React · Vite · Tailwind

**Other**
Power Platform · Power BI · Microsoft Power Automate · Git

---

## Projects

### 🔍 Production RAG Pipeline
Multi-format document ingestion system built for real-world PDFs — 
the ones that are 1,000+ pages and mix native text, scanned pages, tables, 
and images all in one file.

Built a two-pass page classifier using fitz signals (char count, image area, 
line density) to route every page to the right extractor before it ever 
hits an LLM. Hybrid retrieval with BM25 + dense embeddings, 
cross-encoder reranking, and RAGAs evaluation.

**Stack:** LlamaIndex · PyMuPDF · pymupdf4llm · unstructured · 
sentence-transformers · BM25 · Gemini · RAGAs

---

### 📄 Resume Optimizer
AI-powered resume tailoring tool — paste a job description, get back 
a scored analysis, keyword gap breakdown, rewritten bullets, and a 
downloadable DOCX.

FastAPI backend on Railway, React frontend on Vercel, Supabase for auth 
and file storage. The rewriter uses a tuned system prompt to preserve 
natural voice instead of generating generic AI-sounding bullets.

**Stack:** FastAPI · Claude API · React/Vite · Supabase · Railway · Vercel · python-docx

---

### 🎥 CodeBrain
Local, offline-first knowledge base for coding content from Instagram and YouTube. 
Share a Reel from your phone → it transcribes with Whisper, extracts structured 
metadata with a local LLM (Ollama), embeds with nomic-embed-text, 
and stores in ChromaDB. Chat with your personal library of everything you've watched.

**Stack:** yt-dlp · Whisper · Ollama · ChromaDB · FastAPI · React/Vite

---

## Experience

**AI Engineering Extern**
Built RAG pipelines for legal document processing — clause-aware chunking, 
hybrid retrieval, cross-encoder reranking, semantic caching, and RAGAs evaluation.

**IT Co-op @ Mercedes-Benz U.S. International**
Built KPI dashboards and automated workflows using Microsoft Power Platform 
and Power Automate across production operations.

---

## Currently building

- Improving document classifier precision on edge-case PDFs
- Adding agentic retrieval layer to the RAG pipeline
- Open to collaborating on anything LLM / retrieval / AI infra related

---

## Reach me

💼 [linkedin.com/in/meganmulcahy](https://linkedin.com/in/meganmulcahy)  
📍 Dallas, TX (Coming May 2027)
