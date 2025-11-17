# AI Technical Support System

This project implements an AI-powered system that analyzes corporate support tickets, retrieves contextual information from ERP and Freshdesk, and generates accurate responses using Large Language Models (LLMs) combined with a Retrieval-Augmented Generation (RAG) approach. The solution includes a Streamlit frontend, a FastAPI backend, secure API integrations, and automated prompt evaluation using Promptfoo.

---

## 1. Overview

The system processes user queries by:

1. Retrieving ticket data from ERP or Freshdesk.
2. Constructing contextual information through a RAG pipeline.
3. Sending the enriched prompt to an OpenAI LLM.
4. Returning summaries, classifications, or full support responses.

This reduces workload for support teams and ensures accurate and consistent answers.

---

## 2. Main Components

- **Streamlit (Frontend):** User interface for entering ticket IDs and questions.
- **FastAPI (Backend):** Handles authentication, ticket retrieval, context building, and LLM communication.
- **OpenAI LLM:** Generates summaries, categories, or responses.
- **RAG:** Grounds answers in reliable, domain-specific data.
- **Promptfoo:** Evaluates and validates prompt quality.

---

## 3. Installation

### Clone the repository
```bash
git clone https://github.com/<your-repo>/support-ai-system.git
cd support-ai-system
