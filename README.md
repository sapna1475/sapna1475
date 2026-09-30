<h1 align="center">Hi, I'm Sapna  👋</h1>
<h3 align="center">AI/LLM Engineer & Backend Developer | Building Agentic AI, RAG & Real-Time Applications</h3>

<p align="center">
  <a href="https://linkedin.com/in/sapna-tiwari"><img src="https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:sapna1475tiwari@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" /></a>
  <a href="https://leetcode.com/u/sapna1475tiwari"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=black" /></a>
  <img src="https://img.shields.io/badge/CGPA-9.03-brightgreen?style=flat" />
</p>

---
### Resume
[View my resume](./Sapna_Resume_ASE.pdf)

### 🧭 About Me

I'm Sapna Tiwari, a B.Tech Computer Science student at VIT (2023 – 2027) interested in Agentic AI, Retrieval-Augmented Generation (RAG), and full-stack development. I build multi-agent systems and RAG pipelines with LangGraph, LangChain, FAISS, and open-source LLMs, and I take them all the way to production with FastAPI, Docker, and AWS. I care about reliability: validated structured outputs, human-in-the-loop control, tracing, and measurable evaluation.

---

### 🛠️ Tech Stack

**Languages & Frontend**
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Backend & Databases**
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Socket.io](https://img.shields.io/badge/-Socket.io-010101?style=flat-square&logo=socket.io&logoColor=white)
![WebRTC](https://img.shields.io/badge/-WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white)
![JWT](https://img.shields.io/badge/-JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

**AI / GenAI**
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/-LangGraph-6F42C1?style=flat-square)
![Hugging Face](https://img.shields.io/badge/-Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Gemini](https://img.shields.io/badge/-Google%20Gemini%20API-4285F4?style=flat-square&logo=google&logoColor=white)
![FAISS](https://img.shields.io/badge/-FAISS%20Vector%20Search-FF6F00?style=flat-square)
![Prompt Engineering](https://img.shields.io/badge/-Prompt%20Engineering-6A0DAD?style=flat-square)

**LLM Evaluation & Observability**
![LangSmith](https://img.shields.io/badge/-LangSmith-1C3C3C?style=flat-square)
![RAGAS](https://img.shields.io/badge/-RAGAS-0F766E?style=flat-square)

**Cloud & DevOps**
![AWS](https://img.shields.io/badge/-AWS%20(ECR%2C%20ECS%20Fargate%2C%20Bedrock)-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Render](https://img.shields.io/badge/-Render-46E3B7?style=flat-square&logo=render&logoColor=black)
![Git](https://img.shields.io/badge/-Git%2FGitHub-181717?style=flat-square&logo=github&logoColor=white)
![CI/CD](https://img.shields.io/badge/-CI%2FCD%20(GitHub%20Actions)-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Core CS:** Data Structures & Algorithms (150+ problems solved) · Computer Networks · DBMS · Operating Systems

---

### 🚀 Featured Projects

#### 🔗 [Blog Writing Agent](https://github.com/sapna1475/Blog_Writing_Agent) · [Live demo (AWS)](http://blog-writing-agent-lb-428148850.us-east-1.elb.amazonaws.com/health)
`LangGraph` `LangSmith` `FastAPI` `Streamlit` `Docker` `AWS ECS Fargate` `PostgreSQL` `Hugging Face` `Gemini`

An autonomous multi-agent blog writer: it researches, drafts a plan, pauses for your approval, then writes every section in parallel. Runs on open-source Qwen2.5-7B, so no paid LLM API is needed.
- Cut blog-generation latency **68%** (40 → 13 min, 50 topics) with parallel section-writer agents in a LangGraph pipeline
- Reduced citation hallucinations **92%** and raised parse success **61% → 98%** via Pydantic validation and human-in-the-loop approval with Postgres-backed short-term memory
- Raised citation validity **74% → 93%** using LangSmith tracing and automated evals (30 topics, 6 prompt iterations)
- Containerized with Docker and deployed on **AWS** (ECR, ECS Fargate, Application Load Balancer)

---
#### 🔗 [YouTube RAG Assistant](https://github.com/sapna1475/RAG_YOUTUBE_CHAT) · [Live API docs](https://youtube-rag-backend-mvqq.onrender.com/docs)
`FastAPI` `LangChain` `FAISS` `Hugging Face` `RAGAS` `JavaScript` `HTML`

A full-stack RAG system for transcript-grounded Q&A over YouTube videos.
- Delivered grounded Q&A across **500+ YouTube videos** by combining FAISS vector search, embeddings, and Qwen 2.5 7B inference
- Achieved **70% Precision@2, 81.1% faithfulness, and 78.5% answer relevancy** (RAGAS) through an evaluation pipeline on 100 hand-labeled questions
- Cut repeated-query latency **85%** (20s → 3s) by caching per-video FAISS indexes across 24,832 transcript chunks

---
#### 🔗 [AI Habit Tracker](https://github.com/sapna1475/AI-HabitTracker)
`MERN` `Google Gemini 2.5 Flash` `PWA` `VAPID` `JWT` `bcrypt`

A habit-tracking PWA built to solve a real drop-off problem: people abandoning trackers after missing a single day.
- 5 personalized AI features (streak-recovery coaching, habit analysis chat) powered by Gemini 2.5 Flash, with sub-2-second responses using Express rate-limiting middleware and real user data in prompts for non-generic output
- Sustained **94.6% success** across 300+ simulated AI requests with circuit-breaker logic and automatic fallback recovery
- Idempotent streak-reminder system (node-cron + VAPID Web Push) with per-user-per-day state checks, giving **zero duplicate notifications** across 1,000 simulated users
- MongoDB Atlas persistence with date-fns-driven streak calculation logic

---
#### 🔗 [DevCollab — Real-Time Collaborative Code Editor](https://github.com/sapna1475/DEVCOLLAB)
`MERN` `Socket.io` `WebRTC` `Monaco Editor` `JWT` `Razorpay`

A live, multi-user code editor built to replace the friction of screen-sharing and copy-pasting code.
- 3-tier role-based access (owner/editor/viewer) with live cursor tracking
- Secure JWT auth (bcrypt hashing + refresh tokens) for persistent sessions
- Peer-to-peer video/voice calling via WebRTC
- Versioned code history in MongoDB with rollback support
- Razorpay integration with server-side signature verification for premium features

---

### 🏆 Beyond Code

- 🌐 **ICDCC 2024**: Website Development Team Member; built the homepage & speaker section for a conference site that handled 5,000+ visits
- 🔐 **Cyber Carnival '26 (VIT Bhopal Cyber Security Club)**: Event Management Lead; drove 1,000+ student registrations through social media campaigns and college partnerships
- 📜 **Certifications:** Google IT Support · Bits and Bytes of Computer Networking · Deloitte Data Analytics Job Simulation

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sapna1475&show_icons=true&theme=default&hide_border=true" height="165"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=sapna1475&hide_border=true" height="165"/>
</p>

---

### 📫 Let's Connect

I'm looking for **SDE / AI Engineer / Full-Stack Developer internship & entry-level roles** where I can keep building products end-to-end. Happy to walk through the technical decisions behind any project above.

📧 **sapna1475tiwari@gmail.com** &nbsp;|&nbsp; 📱 +91 8619731475
