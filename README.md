# AI-Powered Support Assistant

**What it does:** Classifies support tickets, drafts empathetic responses using GenAI, and pulls live ERP/CRM context via APIs.

**Why it matters:** Reduces manual triage, speeds resolution, and makes AI usable in real workflows—exactly what Customer Solutions and AI Engineering teams need.

## Features
- Ticket classification (billing, technical, account, shipping)
- LLM-assisted responses with templates and tone guardrails
- ERP/CRM API integration (mocked, easily replaceable)
- Streamlit dashboard for agents and managers
- Metrics and logs for quality tracking

## Tech Stack
FastAPI, Streamlit, scikit-learn, OpenAI, SQLAlchemy, PostgreSQL, Docker

## Quickstart
1. `cp .env.example .env` and add `OPENAI_API_KEY`
2. `docker-compose up --build`
3. Open `http://localhost:8501` for the dashboard

## Roadmap
- Fine-tuned intent model
- Human-in-the-loop approval
- Role-based access and audit logs
