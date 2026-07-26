<div align="center">

# Saswata Mondal

### AI & Backend Engineer · LLMs, Agentic Systems, Scalable Backends

**System Software Engineer Intern @ AMI** (American Megatrends International)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saswatamondal/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://saswatamondal.me/)
[![SyntaxHut](https://img.shields.io/badge/SyntaxHut-6E56CF?style=for-the-badge&logo=googlechrome&logoColor=white)](https://syntaxhut.tech)
[![LeetCode](https://img.shields.io/badge/LeetCode%201672-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/saswatamondal/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:msaswata15@gmail.com)

![Profile Views](https://komarev.com/ghpvc/?username=msaswata15&color=blueviolet&style=for-the-badge)

</div>

---

## About Me

I build **intelligent systems at the intersection of backend engineering and applied AI** — LLM agents that actually ship, and the infrastructure that keeps them fast, private and reliable.

Currently a **System Software Engineer Intern at AMI** (American Megatrends International) in Kolkata. Everything showcased below is my own open-source and personal work.

```yaml
name: Saswata Mondal
location: Kolkata, India
role: System Software Engineer Intern @ AMI
education: B.Tech CSE @ IEM Kolkata (2022–2026), CGPA 9.18/10
focus: [LLM agents, RAG, backend systems, system design]
languages: [Python, Go, Java, JavaScript/TypeScript, SQL]
currently: building agentic RAG systems and scalable Python/Go backends
dsa: 500+ problems · LeetCode 1672 (top 15% globally)
research: 2 peer-reviewed papers accepted @ EIRTM 2026
```

---

## Featured Projects

### [SyntaxHut](https://github.com/msaswata15/syntaxhut) — AI-assisted DSA learning platform · [syntaxhut.tech](https://syntaxhut.tech)
`Next.js 15` `React 19` `TypeScript` `Python` `Gemini` `GitHub Actions` `PostgreSQL` `Cloudflare`

Production content platform with **2,800+ problem pages**, 470 company-tagged sets and 390+ automated blog posts, serving **3,400+ users / 41,000+ requests / 12 GB+ traffic**.

- Contextual **AI tutor** grounded in the problem, difficulty and solution code on screen.
- **Automated content pipeline**: [`leetcode-solutions`](https://github.com/msaswata15/leetcode-solutions) scrapes, solves, verifies via LeetCode submission, enriches with Gemini, then pushes the regenerated corpus into the frontend repo weekly — reducing manual effort by ~70%.
- **Quality-as-CI**: per-problem enrichment scoring with a CI gate that fails PRs on thin-content regression (baseline 0.19%).
- Full SEO stack: sharded sitemaps, JSON-LD, IndexNow + Google Indexing API on every deploy.

### [Agentic RAG Research Chat API](https://github.com/msaswata15/local-research-chat-api) — document-grounded conversational AI
`Python` `FastAPI` `LangGraph` `Ollama` `ChromaDB` `MLflow` `Docker`

Local-first RAG platform for grounded PDF/TXT chat with a **multi-agent validation architecture** (retrieval → generation → self-critique → iterative refinement) to cut hallucinations, containerized inference APIs, monitoring and experiment tracking.

### [AI Virtual Development Pod](https://github.com/msaswata15/AI_VIRTUAL_DEVELOPMENT_POD) — multi-agent SDLC automation
`Python` `Multi-Agent Systems` `LLM Orchestration`

Framework simulating **Business Analyst, Designer, Developer, QA and Security Engineer** roles through autonomous inter-agent collaboration, with task decomposition and iterative critique loops that improve artifact quality.

### [AI Career Companion](https://github.com/msaswata15/AI-Career-Companion-Proctor-Mock) — AI job-search suite
`Python` `Streamlit` `LLMs` `NLP`

Automated job matching, tailored resume/cover-letter generation, interview cheat sheets, and **voice-based proctored mock interviews**.

### Backend engineering
| Project | Stack | Focus |
| --- | --- | --- |
| [Inventory Service (Go)](https://github.com/msaswata15/Inventory_DB-GO) | Go, PostgreSQL, SMTP | Clean architecture, async email notifications |
| [Inventory Service (Python)](https://github.com/msaswata15/inventory_project) | SQLAlchemy, Alembic, PostgreSQL | ACID transactions, schema migrations |
| [Smart Clinic Management](https://github.com/msaswata15/Smart-Clinic-Management-System) | Spring Boot, Java 17, MySQL, MongoDB, Docker | REST APIs + Thymeleaf dashboards |
| [Library Management System](https://github.com/msaswata15/LibraryManagementSystem) | Spring Boot | Books, members, borrowing records |
| [FastAPI Digital Library](https://github.com/msaswata15/fastapi-digital-library) | FastAPI | CRUD, validation, HTTP error semantics |
| [Dockerized To-Do App](https://github.com/msaswata15/ToDoApp_Using_Docker) | Vue 3, FastAPI, PostgreSQL, Compose | Full containerized stack |

### AI/ML & product
| Project | Stack | Focus |
| --- | --- | --- |
| [Sign Language Translator](https://github.com/msaswata15/sign_translator) · [ASLOMPRESS](https://github.com/msaswata15/ASLOMPRESS) | Python, YOLOv8, quantization | Research code behind the edge-inference paper |
| [LeetHint Chrome Extension](https://github.com/msaswata15/leet-hint-extension) | JavaScript, LLM APIs | In-browser contextual hints for LeetCode |
| [AI Booking Assistant](https://github.com/msaswata15/AI-Booking-Assistant) | FastAPI, LangGraph, Streamlit | Conversational Google Calendar booking |
| [E-Commerce Platform](https://github.com/msaswata15/E-Com-using-Mern) | MERN, Tailwind | Auth, cart, PayPal/Razorpay, admin dashboard |
| [Hospital Management](https://github.com/msaswata15/Full-Stack-Hospital-Management) | MERN | Appointments, records, role dashboards |
| [Car Price Prediction](https://github.com/msaswata15/car-price-analysis) | XGBoost, Ridge, Streamlit | Model comparison + interactive UI |

<div align="center">

### [View all repositories →](https://github.com/msaswata15?tab=repositories)

</div>

---

## Research Publications

**Attention-Guided Knowledge Distillation for Real-Time Sign Language Recognition on Edge Devices** — peer reviewed, *EIRTM 2026*
> Lightweight CV framework compressing YOLOv8-Medium with INT8 quantization: **99.50% mAP@0.5, 45.4% model compression, 54.9 FPS** inference.

**A Game-Inspired Psychometric Assessment Framework for AI-Based Academic Course Recommendation** — peer reviewed, *EIRTM 2026*
> Explainable recommendation framework combining cognitive testing, Big Five personality profiling and transparent reasoning pipelines.

---

## Achievements

- **Director's Award for Best Student Contribution** — IEM (2026)
- **Top 11 Finalist (Pan India)** — Capgemini Brand Quest 2026
- **NPTEL Silver Elite** — top 5% performer
- **Qualified internal round** — Smart India Hackathon 2024
- **LeetCode 1672 rating**, top 15% globally · 500+ problems across DP, graphs, trees, greedy, binary search, advanced data structures
- **ISC school topper & House Captain** (2021–22) · ISC 94.75%, ICSE 92.4%

---

## Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**AI / LLM Engineering**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)

`Agentic AI` · `RAG` · `Prompt Engineering` · `Fine-tuning` · `Local LLM inference` · `Vector databases` · `NLP`

**Backend & Infrastructure**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=for-the-badge&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

**Core CS:** DSA · Operating Systems · DBMS · Computer Networks · OOP · System Design

</div>

---

## GitHub Stats

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=msaswata15&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" />
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=msaswata15&theme=tokyonight&hide_border=true" />

<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=msaswata15&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />
<img width="49%" src="https://github-readme-activity-graph.vercel.app/graph?username=msaswata15&theme=tokyo-night&hide_border=true&area=true" />

<img src="https://github-profile-trophy.vercel.app/?username=msaswata15&theme=algolia&no-frame=true&column=7&margin-w=15&margin-h=15" alt="GitHub Trophies" />

![GitHub Snake Light](https://raw.githubusercontent.com/msaswata15/msaswata15/output/github-snake.svg#gh-light-mode-only)
![GitHub Snake Dark](https://raw.githubusercontent.com/msaswata15/msaswata15/output/github-snake-dark.svg#gh-dark-mode-only)

[![LeetCode Stats](https://leetcard.jacoblin.cool/saswatamondal?theme=dark&font=Noto%20Sans&ext=activity)](https://leetcode.com/u/saswatamondal/)

</div>

---

## Education

**Institute of Engineering and Management (IEM), Kolkata** — B.Tech, Computer Science & Engineering · 2022–2026 · **CGPA 9.18/10**

**The Assembly of God Church School, Haldia** — ISC 94.75% · ICSE 92.4%

---

<div align="center">

## Let's Connect

**Open to AI/LLM engineering and backend roles.** Happy to talk about agentic systems, RAG pipelines, or scaling backends.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saswatamondal/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://saswatamondal.me/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:msaswata15@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/saswatamondal/)

*"Build systems that are intelligent, but also honest about what they know."*

**From [msaswata15](https://github.com/msaswata15) — Kolkata, India**

</div>
