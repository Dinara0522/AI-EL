# AI-EL - AI-Powered Women's Safety Platform

**AI-powered women's safety and emergency support platform for Kazakhstan.**

AI-EL is a bilingual mobile application concept designed to help women in Kazakhstan access safety information, emergency support resources, and AI-powered assistance.

> Әйел — ел болашағы.

## Project Overview

AI-EL combines mobile technology and artificial intelligence to provide:

- Emergency support workflows and trusted contacts.
- User-authorized location sharing.
- AI-powered legal and safety information assistance.
- Retrieval-Augmented Generation (RAG) using official Kazakhstan sources.
- AI agent tools for information retrieval.
- Document information extraction using OCR.

## Target Users

Women in Kazakhstan who need accessible safety information, emergency support resources, and guidance.

## Planned Technology Stack

| Component | Technology |
|---|---|
| Mobile application | Flutter / Dart |
| Backend | Python / FastAPI |
| Database | PostgreSQL |
| Vector search | pgvector |
| AI | LLM API and embeddings |
| Document processing | OCR |
| Version control | Git / GitHub |

## AI Features

### 1. AI Assistant

Provides answers to safety-related and legal information questions in Kazakh and Russian.

### 2. Retrieval-Augmented Generation (RAG)

Retrieves relevant information from a curated knowledge base and generates answers with source references.

### 3. AI Agent

Uses specialized tools to retrieve legal information and support resources.

### 4. Document AI

Explores OCR-based extraction of information from documents.

## Information Sources

- [Government of Kazakhstan](https://www.gov.kz/)
- [Adilet Legal Information System](https://adilet.zan.kz/)

## Team

| Member | Responsibility |
|---|---|
| Dinara Bergen | AI, backend, RAG, agent tools, evaluation |
| Symbat | Mobile application, UI, SOS, GPS, integration |

## Repository Structure

```text
AI-EL/
├── README.md
├── PLAN.md
├── AGENTS.md
├── DECISIONS.md
├── REFLECTION.md
├── docs/
│   └── PROPOSAL.md
├── agent-logs/
├── backend/
├── mobile/
├── tests/
└── evaluation/
```

## Project Status

**Planning and proposal stage.**

The features and technologies described above are planned and are not yet claimed to be implemented.

## Development Timeline

The project is planned over five weeks:

1. Project setup and architecture.
2. Mobile interface and emergency workflows.
3. AI assistant and RAG.
4. Agent tools and document processing.
5. Testing, evaluation, and final demonstration.

## AI Development Process

The team plans to use an agentic coding tool to plan, write, run, and debug code directly in this repository.

Important decisions, agent sessions, tests, and reflections will be documented throughout development.

## Disclaimer

AI-EL is an academic prototype. It is not an emergency dispatch service, and its AI-generated information does not replace professional legal advice or official emergency assistance.
