<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:2C5364,100:00C9A7&height=220&section=header&text=Sai%20Santhosh&fontSize=55&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Python%20%26%20ML%20Engineer%20%7C%20Generative%20AI%20%2F%20LLM%20Systems&descAlignY=58&descSize=18" width="100%"/>

<a href="https://santhosh-gemini-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://linkedin.com/in/sai-santhosh-achari"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:saisanthosh.023@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/syrusdhark"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=2800&pause=900&color=2C5364&center=true&vCenter=true&width=780&lines=Building+LangGraph+agentic+pipelines+%40+Zgrow;Founder+%40+HIRA+%E2%80%94+AI+health+coaching+platform;RAG+%2B+Postgres+%2B+Terraform+%2B+AWS%2C+end+to+end;Published+researcher+in+healthcare+AI" alt="typing-svg"/>

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:2C5364,100:00C9A7&height=3&width=100%"/>

## 🧭 About Me

```python
class SaiSanthosh:
    def __init__(self):
        self.role      = "Gen AI Engineer @ Zgrow"
        self.building  = ["AI365 (LangGraph + RAG)", "HIRA (AI health coach)"]
        self.based_in  = "Chennai, India"
        self.education = "B.Tech CSE, SRM IST Ramapuram — CGPA 9.3/10"
        self.motto     = "own the system end-to-end: schema -> cloud -> observability"

    def currently(self):
        return "architecting multi-step LLM reasoning pipelines & shipping agents to prod"
```

I'm a Python and Machine Learning engineer who builds **production** Generative AI systems — not notebooks that stay notebooks. Think LangGraph agentic pipelines, RAG with polyglot persistence, and evaluation-driven LLM development, backed by real infrastructure: Terraform, AWS, load testing, observability.

- 🧠 **Gen AI Engineer @ Zgrow** — architecting **AI365**, an LLM-powered education platform (multi-step reasoning, RAG, tool-calling)
- 🩺 **Founder, HIRA** — a LangGraph health-coaching agent grounded strictly in a user's own logged data
- 🏗️ **Founder, House of Sri** — where I also cut my teeth as a full-stack developer
- 📄 **Published researcher** — *HIRA: Intelligent Healthcare Chatbot* (FMDB 2024) · DR-TB detection system presented at AIIMS Delhi 2025

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:2C5364,100:00C9A7&height=3&width=100%"/>

## 🧰 Tech Stack

<div align="center">

**AI / ML / GenAI**
<br/>
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,py"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/OpenAI%20API-412991?style=for-the-badge&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/Gemini%20API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white"/>
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>

**Backend & Data**
<br/>
<img src="https://skillicons.dev/icons?i=fastapi,flask,postgres,mongodb,redis,supabase"/>

**Infra & DevOps**
<br/>
<img src="https://skillicons.dev/icons?i=aws,terraform,docker,githubactions,git"/>

**Frontend**
<br/>
<img src="https://skillicons.dev/icons?i=ts,react,nextjs,swift"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:2C5364,100:00C9A7&height=3&width=100%"/>

## 🌟 Featured Builds

<table>
<tr>
<td width="50%" valign="top">

### 🩺 HIRA
**AI Health Coaching Platform**

A LangGraph tool-calling agent (OpenAI-backed) that answers health questions grounded strictly in a user's own logged metrics and semantically-retrieved history.

- Dual retrieval: Postgres tool calls + ChromaDB/Ollama vector search, served via FastAPI
- LLM-judged eval harness for faithfulness, relevancy & diagnostic-refusal compliance
- Redis caching/rate-limiting with graceful degradation, RQ background workers, per-call observability in MongoDB
- Deployed to AWS via Terraform (ECS Fargate, RDS, ElastiCache, ALB); load-tested with Locust
- Shipped to React Native + Swift clients, active users

</td>
<td width="50%" valign="top">

### 🏢 Real Estate CRM
**Multi-tenant SaaS**

Org-scoped Postgres RLS, JWT auth via JWKS, RBAC, and an audit log on every mutation, no exceptions.

- Domain correctness at the API layer: integer-paise money, forward-only deal-stage transitions, terminal-state guards
- Google Gemini AI proxy, org-scoped & context-window-managed
- 32 API routes · 13 frontend screens (React + React Native/Expo) · 220 passing tests

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 🫁 DR-TB Detection System
**Deep Learning · Computer Vision · Healthcare**

An end-to-end pipeline for drug-resistant tuberculosis detection from chest X-rays — preprocessing, CNN training, evaluation, and automated clinical report generation, deployed via Streamlit for real-world clinic use. **Presented at AIIMS Delhi 2025** (poster & oral).

</td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:2C5364,100:00C9A7&height=3&width=100%"/>

## 📚 Publications

> **HIRA: Intelligent Healthcare Chatbot** — FMDB 2024 Conference
> Research on LLM-powered health diagnostics, conversational AI for medical guidance, and agentic architecture for healthcare applications.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:2C5364,100:00C9A7&height=3&width=100%"/>

<div align="center">

### 📫 Let's talk

<a href="https://santhosh-gemini-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://linkedin.com/in/sai-santhosh-achari"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:saisanthosh.023@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C9A7,50:2C5364,100:0F2027&height=100&section=footer" width="100%"/>

</div>
