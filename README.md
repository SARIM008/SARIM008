# Mohammad Sarim

ML Engineer building production AI systems (LLM workflows, evals, backend).

## Featured work: AbhiGhar AI assistant (production)

A production Gemini chatbot for a Pune real-estate platform, live at [abhighar.com](https://abhighar.com).
Built at work for a client, so the code is private; this section describes how the system works.

- **Design:** the LLM only extracts intent and entities through a fixed schema; deterministic code owns every action and every fact.
- **Evals:** 885-message eval set; intent accuracy improved from 80% to 91%.
- **Multilingual:** Marathi handling improved from 61% to 99%.
- **Reliability and security:** retries, model fallback, and security hardening.
- **Stack:** Python, FastAPI, asyncio, Gemini, PostgreSQL, React/TypeScript, Docker.

## Projects

| Project | What it does | Stack |
|---|---|---|
| [Hospital Management System](https://github.com/21f2001224-cmd/team-CodeCrew-se-project) (team CodeCrew) | 🏆 Best Course Project, Software Engineering (Rank 1), IIT Madras. Team project; I was Scrum Master. Role-based app for admins, doctors, staff and patients, with a RAG assistant over hospital SOP documents (hybrid BM25 + vector retrieval) and Whisper-transcribed consultations summarised by an LLM. | Flask, Vue, SQLAlchemy, JWT, LangChain, ChromaDB, Whisper, DeepSeek |
| [Quiz Master](https://github.com/SARIM008/quiz-master) | Quiz platform with a REST API, role-based auth, Redis caching and Celery background jobs: daily Google Chat reminders, monthly email reports and async CSV exports. | Flask, Flask-Security, Celery, Redis, Vue.js, SQLite |
| [Influencer–Sponsor Platform](https://github.com/SARIM008/Sponsor-influencer-Management-Platform) | 🏆 Best Course Project, Modern Application Development I, IIT Madras. Campaign marketplace with admin, sponsor and influencer roles, two-way ad requests, and admin moderation. | Flask, SQLAlchemy, SQLite, Jinja |
| [DSA in Python](https://github.com/SARIM008/Striver-dsa-python) | Data structures and algorithms practice following Striver's A2Z DSA Sheet, organised by topic. | Python |

## Cloud & MLOps (IIT Madras MLOps course; graded exam work, so the code stays private)

- Deployed a containerised Flask model API to Google Kubernetes Engine: Docker image in Artifact Registry, LoadBalancer service, readiness and liveness probes, Horizontal Pod Autoscaling, GitHub Actions CI/CD, and load testing.
- Built an end-to-end ML pipeline with DVC (Google Cloud Storage remote), a Feast feature store, MLflow experiment tracking and model registry, pytest checks, and CML reports on pull requests.
- Explained models with SHAP and checked fairness with Fairlearn.

## Skills

Python · FastAPI · SQL/PostgreSQL · LLMs/Gemini · Evals · Celery · Redis · Docker · Kubernetes · Google Cloud · React/TypeScript

## Awards

- Best Course Project, Software Engineering (Rank 1), IIT Madras
- Best Course Project, Modern Application Development I, IIT Madras

## Contact

[LinkedIn](https://www.linkedin.com/in/mohammad-sarim-0b46ab1b9)
