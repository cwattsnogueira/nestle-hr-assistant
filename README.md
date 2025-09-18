#  Nestlé HR Assistant

[![Colab Flan-T5](https://img.shields.io/badge/Colab-Flan--T5%20Version-blue?logo=googlecolab)](https://colab.research.google.com/github/cwattsnogueira/nestle-hr-assistant/blob/main/Unit6FinalProject04.ipynb)
[![Colab GPT-3.5](https://img.shields.io/badge/Colab-GPT--3.5%20Version-green?logo=googlecolab)](https://colab.research.google.com/github/cwattsnogueira/nestle-hr-assistant/blob/main/Unit6FinalProjectOpenAI.ipynb)
[![License: MIT](https://img.shields.io/badge/License-MIT-lightgrey.svg)](https://github.com/cwattsnogueira/nestle-hr-assistant/blob/main/LICENSE)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen)](https://github.com/cwattsnogueira/nestle-hr-assistant)

##  Tecnologias e Frameworks

[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)](https://www.python.org/)
[![LangChain](https://img.shields.io/badge/LangChain-integrated-green?logo=python)](https://www.langchain.com/)
[![Gradio](https://img.shields.io/badge/Gradio-UI-orange?logo=gradio)](https://www.gradio.app/)
[![OpenAI](https://img.shields.io/badge/OpenAI-GPT--3.5-blue?logo=openai)](https://platform.openai.com/)
[![FAISS](https://img.shields.io/badge/FAISS-Vector%20Search-purple)](https://github.com/facebookresearch/faiss)
[![ChromaDB](https://img.shields.io/badge/ChromaDB-Retrieval-green)](https://www.trychroma.com/)


> Generative AI Capstone · University of San Diego / Fullstack Academy  
> Developed by **Carllos Watts-Nogueira** · September 2025

---

##  Overview

This project delivers a conversational HR assistant that answers questions based on Nestlé’s internal HR policy documents. It uses retrieval-augmented generation (RAG) to extract relevant policy excerpts and generate grounded responses. Two versions were developed:

- **Flan-T5 + FAISS**: lightweight, open-source pipeline for document-based QA
- **GPT-3.5 Turbo + ChromaDB**: scalable, API-powered assistant with enhanced fluency

Both versions are deployed in Google Colab with Gradio interfaces for real-time interaction.

---

##  Repository Structure

| File | Description | Access Link |
|------|-------------|-------------|
| [`Unit6FinalProject04.ipynb`](https://github.com/cwattsnogueira/nestle-hr-assistant/blob/main/Unit6FinalProject04.ipynb) | HR assistant using Flan-T5, FAISS, and sentence-transformers | <a href="https://colab.research.google.com/github/cwattsnogueira/nestle-hr-assistant/blob/main/Unit6FinalProject04.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| [`Unit6FinalProjectOpenAI.ipynb`](https://github.com/cwattsnogueira/nestle-hr-assistant/blob/main/Unit6FinalProjectOpenAI.ipynb) | HR assistant using GPT-3.5 Turbo, ChromaDB, and LangChain | <a href="https://colab.research.google.com/github/cwattsnogueira/nestle-hr-assistant/blob/main/Unit6FinalProjectOpenAI.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
|[`the_nestle_hr_policy_pdf_2012.pdf`](https://github.com/cwattsnogueira/nestle-hr-assistant/blob/main/the_nestle_hr_policy_pdf_2012.pdf)  |Source document used for retrieval-based Q&A| - |

---

## 🛠️ Technologies & Skills

- Python
- Hugging Face Transformers
- OpenAI API
- LangChain
- FAISS
- ChromaDB
- Sentence Transformers
- Gradio
- Retrieval-Augmented Generation (RAG)
- Prompt Engineering
- Modular Design
- Deployment
- Reproducibility

---

##  Capstone Tasks

-  Document ingestion and chunking (PDF → semantic segments)
-  Embedding with MiniLM and OpenAI
-  Vector search with FAISS and ChromaDB
-  Prompt-based QA with Flan-T5 and GPT-3.5 Turbo
-  Gradio chatbot interface with fallback logic
-  Evaluation of retrieval quality and model fluency

---

##  License

This project is licensed under the [MIT License](https://github.com/cwattsnogueira/bikeease-ad-generator/blob/main/LICENSE).

---

##  Author

**Carllos Watts-Nogueira**  
AI/ML Engineer · Capstone Project — September 2025  

