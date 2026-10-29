# PalmMind RAG API

A modular FastAPI backend implementing document ingestion, vector search, conversational RAG, Redis-based chat memory, and interview booking.

## Features

- PDF and TXT document ingestion
- Fixed-size and sentence-based chunking
- Sentence Transformer embeddings
- Qdrant vector database
- SQLite document and booking storage
- Custom RAG pipeline
- Redis-based multi-turn conversation memory
- LLM-based interview booking extraction
- FastAPI REST API

## Project Structure

```text
app/
├── api/routes/        # API endpoints
├── core/              # Configuration
├── db/                # Database setup
├── models/            # Database models
├── services/          # RAG, embeddings, Qdrant, Redis, booking
└── main.py            # FastAPI application# palmmind_task
