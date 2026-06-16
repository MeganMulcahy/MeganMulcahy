<!-- GitHub Profile README for Megan Mulcahy -->
<!-- Copy this entire file into your MeganMulcahy/MeganMulcahy repo as README.md -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:16213e,100:0f3460&height=200&section=header&text=Megan%20Mulcahy&fontSize=48&fontColor=e94560&animation=fadeIn&fontAlignY=38&desc=AI%20Engineer%20%7C%20RAG%20%7C%20LLM%20Apps%20%7C%20Dallas&descAlignY=58&descSize=18&descColor=a8b2d8" width="100%"/>

</div>

<br/>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/meganmulcahy)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:youremail@email.com)
[![Portfolio](https://img.shields.io/badge/Resume_Optimizer-4285F4?style=for-the-badge&logo=vercel&logoColor=white)](https://your-resume-optimizer-link.vercel.app)

</div>

<br/>

---

## 👋 About me

CS grad + MBA candidate at University of Alabama. I build AI systems — mostly RAG pipelines, LLM applications, and the tooling that makes them actually work in production.

My background is split between technical AI work and real enterprise environments (Mercedes-Benz operations, LLM evaluation externship), which means I can build things that work and explain why they work.

Relocating to **Dallas** and looking for AI Engineer roles.

---

## 🔧 What I build with

<div align="center">

### AI / ML
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-FF6B6B?style=for-the-badge&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Google Gemini](https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_API-CC785C?style=for-the-badge&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

### Backend & Infra
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Tools & Other
![Power Platform](https://img.shields.io/badge/Power_Platform-742774?style=for-the-badge&logo=microsoft&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper-412991?style=for-the-badge&logo=openai&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=for-the-badge&logoColor=white)

</div>

---

## 🚀 Projects

<table>
<tr>
<td width="50%" valign="top">

### 🔍 Production RAG Pipeline
Multi-format document ingestion built for real-world PDFs — 1000+ pages with mixed native text, scanned pages, tables, and images.

Two-pass page classifier routes every page to the right extractor before it touches an LLM. Hybrid BM25 + dense retrieval, cross-encoder reranking, RAGAs evaluation.

**Stack:** `LlamaIndex` `PyMuPDF` `BM25` `sentence-transformers` `Gemini` `RAGAs`

[![View Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/MeganMulcahy/rag-pipeline)

</td>
<td width="50%" valign="top">

### 📄 Resume Optimizer
Paste a job description → get a scored ATS analysis, keyword gap breakdown, rewritten bullets in your voice, and a downloadable DOCX.

FastAPI backend on Railway, React on Vercel, Supabase for auth and file storage. System prompt tuned to preserve natural voice instead of generic AI output.

**Stack:** `FastAPI` `Claude API` `React` `Supabase` `Railway` `python-docx`

[![Live App](https://img.shields.io/badge/Live_App-4285F4?style=flat-square&logo=vercel&logoColor=white)](https://your-app.vercel.app)
[![View Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/MeganMulcahy/resume-optimizer)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎥 CodeBrain
Local, offline-first knowledge base for coding content. Share an Instagram Reel from your phone → transcribes with Whisper, extracts structured metadata with a local LLM, embeds with nomic-embed-text, stores in ChromaDB. Chat with your personal library.

**Stack:** `yt-dlp` `Whisper` `Ollama` `ChromaDB` `FastAPI` `React`

[![View Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/MeganMulcahy/codebrain)

</td>
<td width="50%" valign="top">

### 🤝 Currently building
- Agentic retrieval layer on top of the RAG pipeline
- Improving page classifier precision on edge-case PDFs
- Open to collaborating on anything LLM / retrieval / AI infra

</td>
</tr>
</table>

---

## 💼 Experience

**AI Engineering Extern**
Built RAG pipelines for legal document processing — clause-aware chunking, hybrid retrieval, cross-encoder reranking, semantic caching, and RAGAs evaluation.

**IT Co-op @ Mercedes-Benz U.S. International**
Built KPI dashboards and automated workflows using Microsoft Power Platform across production operations. Reduced manual reporting time significantly.

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=MeganMulcahy&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=e94560&icon_color=e94560&text_color=a8b2d8" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MeganMulcahy&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=e94560&text_color=a8b2d8" height="165"/>

</div>

<br/>

<div align="center">

*Open to AI Engineer roles in Dallas — reach out anytime*

[![LinkedIn](https://img.shields.io/badge/Let's_connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/meganmulcahy)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f3460,50:16213e,100:1a1a2e&height=100&section=footer" width="100%"/>
