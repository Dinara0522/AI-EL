# AI-EL - Project Plan

## 1. Project Overview

**Project name:** AI-EL  
**Full name:** AI-Powered Women's Safety & Emergency Support Platform  
**Target region:** Kazakhstan

AI-EL is a bilingual mobile safety platform designed to help women access emergency support, safety information, trusted contacts, and AI-powered assistance.

## 2. Problem and Target Users

Women experiencing unsafe situations may need quick access to emergency contacts, reliable legal information, support services, and a secure way to organize important evidence.

**Target users:** Women in Kazakhstan who need safety information, emergency support, or access to assistance resources.

## 3. Core AI Features

- AI assistant for safety-related and legal information.
- Retrieval-Augmented Generation (RAG) using official Kazakhstan sources.
- AI agent with tools for searching laws and support resources.
- OCR and AI-based document information extraction.

## 4. Technology Stack (Planned)

- Mobile application: Flutter
- Backend: Python and FastAPI
- Database: PostgreSQL
- Vector search: pgvector
- AI: LLM API and embeddings
- Document processing: OCR
- Version control: GitHub

The final technology choices may be adjusted during development and documented in DECISIONS.md.

## 5. MVP Scope

The first working version is planned to include:

1. Calculator-style entry interface with PIN access.
2. Russian and Kazakh language support.
3. SOS flow and trusted contacts.
4. Location sharing with user permission.
5. AI assistant with source-grounded answers.
6. RAG over selected official information sources.
7. Basic AI agent tool usage.
8. Initial AI evaluation dataset and tests.

## 6. Stretch Goals

- Advanced document analysis using OCR and VLM.
- Safety plan generation.
- Evidence timeline.
- Expanded support-resource directory.

## 7. AI Evaluation

The AI assistant will be evaluated using a prepared test set of questions in Kazakh and Russian.

Evaluation criteria:
- Answer relevance.
- Factual correctness.
- Retrieval quality.
- Citation correctness.
- Tool selection accuracy.

The team will report measured results rather than assumed performance.

## 8. Data and External Resources

Planned sources:
- Official Kazakhstan government resources: https://www.gov.kz/
- Kazakhstan legal information system: https://adilet.zan.kz/

External APIs and access requirements will be verified before integration.

No real users' sensitive personal data will be used in the evaluation dataset.

## 9. Team Responsibilities

**Dinara:** AI architecture, backend, RAG, embeddings, agent tools, and AI evaluation.

**Symbat:** Mobile application, UI, PIN interface, SOS flow, GPS integration, and document-processing interface.

**Both:** Integration, testing, security, documentation, and final presentation.

## 10. Development Timeline

- Week 1: Project setup, architecture, and interface foundation.
- Week 2: SOS, trusted contacts, and location features.
- Week 3: AI assistant and RAG implementation.
- Week 4: Agent tools, document processing, and evaluation.
- Week 5: Testing, improvements, documentation, and final demonstration.

## 11. Development Approach

The team will use an agentic coding tool to plan, write, run, and debug code directly in the GitHub repository. Important development sessions and decisions will be documented.
