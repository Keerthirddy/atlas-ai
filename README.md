# atlas-ai
Enterprise GenAI platform that autonomously evaluates, monitors, and optimizes RAG systems using Agentic AI, PySpark, Hybrid Retrieval, LLM evaluation, FastAPI, and AI observability.

Overview

Atlas AI is a production-grade GenAI platform designed to improve the reliability, trustworthiness, and performance of Retrieval-Augmented Generation (RAG) systems.

Unlike traditional RAG chatbots that simply generate responses, Atlas AI continuously evaluates, monitors, and optimizes every stage of the RAG lifecycle—from data ingestion and retrieval to LLM evaluation, hallucination detection, and AI observability.

The platform combines modern Data Engineering, Agentic AI, LLM Evaluation, Hybrid Retrieval, and MLOps to build enterprise-ready GenAI applications.



Problem Statement

Enterprise RAG applications frequently suffer from:

- Poor data quality
- Duplicate and inconsistent documents
- Inefficient chunking strategies
- Knowledge drift
- Low retrieval precision
- Hallucinated responses
- Lack of monitoring and observability

Atlas AI provides an autonomous platform that identifies these issues, evaluates system performance, and recommends improvements using specialized AI agents.


Key Features

Data Engineering

- PySpark ETL Pipelines
- Great Expectations Validation
- Metadata Enrichment
- Data Lineage
- Document Deduplication

Knowledge Layer

- Qdrant Vector Database
- Hybrid Retrieval
- BM25 Search
- Dense Retrieval
- Cross-Encoder Reranking

Agentic AI

- Data Quality Agent
- Knowledge Drift Agent
- Chunk Optimization Agent
- Hallucination Detection Agent
- Evaluation Agent

LLM Evaluation

- RAGAS
- DeepEval
- TruLens

Monitoring

- MLflow
- Prometheus
- Grafana

Backend

- FastAPI
- Async APIs
- REST Architecture

 Infrastructure

- Docker
- Docker Compose
- Terraform
- GitHub Actions


High-Level Architecture

Data Sources
      │
      ▼
PySpark ETL Pipeline
      │
      ▼
Great Expectations
      │
      ▼
Metadata + Lineage
      │
      ▼
Chunking Pipeline
      │
      ▼
Embedding Generation
      │
      ▼
Qdrant Vector Database
      │
      ▼
Hybrid Retrieval
      │
      ▼
AI Agents
      │
      ▼
LLM Evaluation
      │
      ▼
Monitoring Dashboard


Tech Stack

| Category | Technologies |
|----------|--------------|
| Programming | Python |
| Backend | FastAPI |
| Data Engineering | PySpark, Great Expectations |
| Retrieval | Qdrant, BM25, Cross Encoder |
| Agent Framework | LangGraph, LangChain |
| Evaluation | RAGAS, DeepEval, TruLens |
| Monitoring | MLflow, Prometheus, Grafana |
| Database | PostgreSQL |
| Infrastructure | Docker, Terraform |
| CI/CD | GitHub Actions |

---

Project Status

🚧 Currently under development.

Development follows a production-first approach with modular architecture, clean code practices, and enterprise software engineering standards.


Roadmap

- Repository Setup
- Data Engineering Pipeline
- Metadata & Lineage
- Chunking Engine
- Embedding Pipeline
- Hybrid Retrieval
- Agentic AI
- LLM Evaluation
- Monitoring Dashboard
- Infrastructure & Deployment


## License
MIT License
