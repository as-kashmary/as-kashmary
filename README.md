# Hi, I'm Anower Sha Shajalal Kashmary 👋

**AI Engineer** · NLP, LLMs and RAG systems · Dhaka, Bangladesh · Open to AI/ML engineering roles

I build and deploy LLM applications with Python, PyTorch and Hugging Face: RAG and conversational systems, fine-tuned language models (LoRA/QLoRA) and the FastAPI services and data pipelines behind them. I'm a first-author published researcher in multilingual NLP, focusing on Bengali.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-as--kashmary-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/as-kashmary/)
[![Email](https://img.shields.io/badge/Email-askashmary%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:askashmary@gmail.com)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-as--kashmary-FFD21E?logo=huggingface&logoColor=black)](https://huggingface.co/as-kashmary)
[![Kaggle](https://img.shields.io/badge/Kaggle-as--kashmary-20BEFF?logo=kaggle&logoColor=white)](https://www.kaggle.com/as-kashmary)

---

### 💼 Experience

- **AI Systems Developer (Contract)**, BETS Consulting Services · Feb–Sep 2026
  Built an AI system that analyzes CVs against terms of reference (TORs): FastAPI, the OpenAI API, Qdrant semantic matching, and Celery/Redis for async jobs. Shipped it in Docker on AWS EC2/Lambda with GitHub Actions CI/CD.
- **Project Associate, R&D (Contract)**, Dotlines Bangladesh · Nov 2025–Jan 2026
  Built core RAG components (LangChain, Pinecone) for a multi-tenant application, plus FastAPI/MySQL REST APIs to serve them.
- **Research Assistant**, Hackules Institute of Advanced Research · Jan–Oct 2025
  Fine-tuned scientific LLMs with LoRA/QLoRA. Built web-scraping and OCR pipelines that produce training data, stored on AWS S3.

---

### 🔬 Featured work

**[Decision Models for Bengali Intent Detection](https://github.com/as-kashmary/Decision-Models-for-Bengali)** (research)
Fine-tuned Qwen3.5-0.8B to score every candidate intent in one forward pass, without generating text. I tested it on English, Bengali, Romanized Bengali and code-mixed text. Joint training reached **85.3% / 79.3% accuracy on English / Bengali** and outperformed sequential transfer and an XLM-R baseline, with all differences significant under exact McNemar tests.
`PyTorch` `Transformers` `Qwen` `Multilingual NLP`

**BenSCI: Bengali Scientific Reasoning Framework** (undergraduate thesis)
A three-agent LLM pipeline for answering Bengali scientific multiple-choice questions on BenQA. I benchmarked five small language models (0.6B–5B) and identified bottlenecks in decoding budget and verifier reliability.
`PyTorch` `LangChain` `Qwen3` `DeepSeek-R1-Distill`

**[RChatbot](https://github.com/as-kashmary/RChatbot)**: a multi-tenant RAG chatbot
A FastAPI app where companies upload product documents through an admin panel and users chat over them. It embeds documents locally with multilingual-e5 for data privacy, retrieves from ChromaDB, streams LLM answers and stores tenants in MySQL.
`FastAPI` `LangChain` `ChromaDB` `Ollama` `MySQL`

**[MT_RAG](https://github.com/as-kashmary/MT_RAG)**: a multi-tenant RAG platform
Separate admin and user services with semantic chunking, hybrid retrieval that fuses BM25 with Pinecone vector search, per-tenant namespaces, query classification and scheduled jobs.
`FastAPI` `LangChain` `Pinecone` `BM25` `Docker`

**[HealthPort](https://github.com/SM-Shaan/HealthPort)**: an intelligent healthcare platform (team project)
A healthcare AI microservice that recommends the right medical department, using semantic search over 493K+ disease–symptom mappings.
`FastAPI` `Sentence Transformers` `ChromaDB`

**[ZenStore AI](https://github.com/as-kashmary/Zenstore-AI)**: an LLM-powered product-data backend
An async FastAPI service that writes marketing descriptions for products with a local Ollama LLM. It processes bulk uploads in the background, uses JWT auth and stores data in MySQL through async SQLAlchemy.
`FastAPI` `Ollama` `SQLAlchemy` `MySQL` `JWT`

---

### 📄 Publication

**CUET_Blitz_Aces@LT-EDI-2025: Leveraging Transformer Ensembles and Majority Voting for Hate Speech Detection.** First author, LT-EDI 2025 shared task (ACL Anthology).

---

### 🛠️ Tech stack

**AI / ML / NLP:** PyTorch, Hugging Face Transformers, LoRA/QLoRA, RAG, LangChain, OpenAI API, Ollama, prompt engineering, LLM evaluation
**Backend & data:** Python, FastAPI, Celery, REST APIs, Pandas, Qdrant, Pinecone, ChromaDB, MySQL, MongoDB, Redis
**DevOps:** Docker, AWS (EC2, Lambda, S3), GitHub Actions, Git
**Also:** C++, JavaScript, Java

---

### 🏆 Highlights
- B.Sc. in Computer Science and Engineering, CUET (CGPA 3.54, 2026)
- Solved 400+ problems on Codeforces, CodeChef and LeetCode
- Ranked 27th of 124 teams in DL Sprint 4.0 Bengali long-form speech recognition, and 27th of 107 in Bengali speaker diarization
- Chair of the ML Wing, IEEE CS CUET Student Branch; Head Organizer of the Datathon at CUET CSE FEST 2025
