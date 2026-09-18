<div align="center">

# Loong

### Python Backend Engineer · AI Agent Engineering

Building production-oriented backend systems, financial integrations,
developer infrastructure, and tool-using AI agents.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/AI_Agents-111111?logo=openai&logoColor=white" />
</p>

</div>

---

## About Me

I'm a Python backend developer interested in building systems that go beyond simple CRUD APIs.

My current focus is on:

- Production-oriented Python backend architecture
- Financial system integrations and multi-party workflows
- Event-driven systems and asynchronous processing
- Tool-using AI Agents and Agent Harnesses
- RAG, structured reasoning, evaluation and safety boundaries
- Developer infrastructure with Docker, PostgreSQL, Redis and messaging systems

I care about turning complex business workflows into systems that are
**traceable, testable, recoverable and maintainable**.

---

## Featured Projects

### [python-fund-mock](https://github.com/loongzcode/python-fund-mock)

A Python-based mock service for multi-funder credit integration testing.

- Implements 26 interfaces for the current SuShang Bank mock integration
- FastAPI + Pydantic + SQLAlchemy + Alembic
- Supports credit, loan, repayment and asynchronous callback workflows
- Includes delayed-success, failure, timeout and other configurable mock scenarios
- Introduces a `FunderAdapter` abstraction for future multi-funder integrations
- Uses persistent state transitions instead of returning static mock JSON

```text
HTTP Request
     ↓
Funder Adapter
     ↓
Domain State
     ↓
Async Task / Callback
     ↓
Persistent Result
