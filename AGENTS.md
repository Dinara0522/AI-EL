# AGENTS.md - AI-EL

## 1. Project Context

You are an AI coding agent working on AI-EL (AI-Powered Women's Safety & Emergency Support Platform), a five-week student project focused on women's safety and access to support resources in Kazakhstan.

The application is planned as a bilingual mobile platform supporting Kazakh and Russian.

Your role is to assist the development team with planning, implementation, testing, debugging, and documentation.

## 2. Main Development Principles

- Read the existing repository structure and documentation before making changes.
- Follow the requirements described in `PLAN.md` and `docs/PROPOSAL.md`.
- Do not introduce features outside the agreed project scope without discussing them with the team.
- Prefer simple, modular, maintainable solutions.
- Explain important technical decisions before implementing complex changes.
- Do not overwrite existing work without checking its purpose.
- Keep documentation consistent with the actual implementation.
- Never claim that a feature works unless it has been implemented and tested.

## 3. Planned Technology Stack

The current planned stack is:

- Mobile application: Flutter and Dart.
- Backend: Python and FastAPI.
- Database: PostgreSQL.
- Vector search: pgvector.
- AI integration: LLM API and embeddings.
- Document processing: OCR.
- Version control: Git and GitHub.

These are planned technologies, not necessarily implemented components. Confirm the selected tools and dependencies with the team before introducing them.

## 4. AI Development Requirements

The AI functionality must provide substantive value beyond a basic chatbot.

Prioritize:

1. Retrieval-Augmented Generation (RAG) using a curated knowledge base.
2. Answers grounded in official Kazakhstan information sources.
3. Source references in generated answers.
4. Agent tool usage for relevant information retrieval tasks.
5. Structured outputs where appropriate.
6. Evaluation using a fixed test dataset and documented criteria.

The assistant must not invent legal articles, emergency contacts, or support resources.

If reliable information is unavailable, clearly communicate the limitation.

## 5. Safety and Privacy Requirements

AI-EL is intended for a sensitive safety-related context.

- Never expose API keys, passwords, tokens, or private configuration values.
- Use environment variables for secrets.
- Do not commit `.env` files or personal information.
- Do not use real users' sensitive personal data in tests.
- Request explicit user permission before accessing or sharing location, documents, camera, or microphone data.
- Do not claim that an SOS message has reached emergency services unless this is verified through an actual supported integration.
- Clearly distinguish notifications sent to trusted contacts from official emergency dispatch.
- Avoid storing unnecessary sensitive information.

## 6. Coding Workflow

For each assigned task:

1. Inspect the relevant files and understand the existing implementation.
2. Describe the proposed approach and files that will be changed.
3. Implement the smallest complete solution.
4. Run relevant tests and checks.
5. Fix errors introduced by the changes.
6. Summarize the implementation and any limitations.
7. Update documentation when necessary.

Do not generate large amounts of unrelated code in a single task.

## 7. Testing and Evaluation

- Write tests for important functionality.
- Test normal cases, invalid inputs, and error conditions.
- Test AI responses against the prepared evaluation dataset.
- Verify that generated answers are supported by retrieved sources.
- Record evaluation results honestly.
- Never fabricate test results or performance metrics.

## 8. Git and Repository Rules

- Use clear and descriptive commit messages.
- Do not delete or rewrite another team member's work without agreement.
- Keep changes focused on the assigned task.
- Do not commit generated secrets, private data, or unnecessary files.
- Preserve meaningful Git history from both team members.

## 9. Communication and Accountability

The coding agent must:

- Explain non-trivial code and architectural decisions.
- Identify assumptions and uncertainties.
- Report failed tests and unresolved issues.
- Highlight security or privacy risks.
- Never silently make important product decisions.
- Help team members understand the code they are responsible for.

The students remain responsible for every implementation, decision, and final submission.

## 10. Documentation

Keep the following project documents updated:

- `README.md` — project overview and setup instructions.
- `PLAN.md` — development plan.
- `DECISIONS.md` — important decisions and lessons from agent use.
- `agent-logs/` — selected agent session transcripts.
- `REFLECTION.md` — final reflection on the agentic development process.

Follow these instructions throughout the development of AI-EL.
