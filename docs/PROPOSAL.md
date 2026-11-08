# AI-EL - Project Proposal

**Project:** AI-EL - AI-Powered Women's Safety & Emergency Support Platform  
**Team:** Dinara Bergen and Symbat  
**Target users:** Women in Kazakhstan  
**Project duration:** 5 weeks

## 1. Problem and Target Users

Women experiencing unsafe or potentially dangerous situations may have difficulty accessing reliable safety information, emergency contacts, legal guidance, and support services quickly.

AI-EL is a bilingual mobile platform designed for women in Kazakhstan. It aims to provide accessible safety resources, emergency assistance features, and AI-powered information support in Kazakh and Russian.

## 2. AI Feature and Evaluation

The main AI feature is an intelligent assistant combining Retrieval-Augmented Generation (RAG) and agent-based tool use.

The assistant will retrieve relevant information from a curated collection of official Kazakhstan legal and public information sources, generate answers, and provide source references.

Planned AI capabilities:
- RAG-based answers about women's rights, safety, and relevant legislation.
- Agent tools for searching legal information and support resources.
- OCR-based extraction of information from uploaded documents.

**Evaluation:** We will prepare a test set of questions in Kazakh and Russian. We will evaluate answer relevance, factual correctness, retrieval quality, citation correctness, and tool selection accuracy using a defined evaluation rubric.

## 3. Agentic Coding Tools

We plan to use **OpenAI Codex** as our primary agentic coding tool, subject to availability under our accounts.

The coding agent will be used directly with the project repository to plan tasks, write code, run tests, debug errors, and improve implementation.

We will document important agent sessions and decisions in `agent-logs/` and `DECISIONS.md`.

## 4. MVP and Stretch Goals

**MVP (required core functionality):**
- Mobile application with a calculator-style entry screen and PIN access.
- Kazakh and Russian language support.
- SOS workflow with trusted contacts.
- User-authorized location sharing.
- AI assistant for safety and legal information.
- RAG over a selected collection of official sources.
- At least one working AI agent tool.
- A small AI evaluation dataset and evaluation report.

**Stretch goals:**
- OCR and AI-based document analysis.
- Personalized safety plan generation.
- Evidence timeline and additional safety resources.

## 5. Data and External APIs

Planned information sources:
- Official Kazakhstan government portal: https://www.gov.kz/
- Kazakhstan legal information system: https://adilet.zan.kz/

Planned external services include a maps/location service, an LLM API, and a notification service.

API availability, access requirements, pricing, and usage limits will be checked before implementation. We will use public information and synthetic test documents for development and evaluation. No real users' sensitive personal data will be collected for the project.

## 6. Team Responsibilities

**Dinara Bergen — AI and Backend:**
- Backend architecture and API development.
- RAG pipeline, embeddings, and vector search.
- AI assistant and agent tool integration.
- AI evaluation and testing.

**Symbat — Mobile Application and Integration:**
- Mobile application architecture and UI.
- Calculator-style interface and PIN access.
- SOS workflow, trusted contacts, and location features.
- Document processing interface and integration.

**Both team members:**
- System integration.
- Testing and security review.
- Documentation, GitHub contributions, and final presentation.

## Expected Outcome

By the end of five weeks, we aim to deliver a locally runnable mobile application prototype demonstrating the core safety workflows and a substantive, evaluated AI assistant.
