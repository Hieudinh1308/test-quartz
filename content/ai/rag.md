---
title: Retrieval Augmented Generation
tags:
  - ai
  - rag
---

# RAG (Retrieval Augmented Generation)

RAG combines:

- Vector Search
- Knowledge Base
- Large Language Models

## Workflow

```text
User Question
      ↓
Embedding
      ↓
Vector Search
      ↓
Retrieve Documents
      ↓
LLM
      ↓
Answer
```

## Components

### Document Storage

Examples:

- MinIO
- S3
- Local Files

### Vector Database

Examples:

- Qdrant
- Chroma
- Weaviate

### LLM

Examples:

- GPT
- Claude
- Llama

## Benefits

- Reduced hallucination
- Uses private data
- More accurate answers

## Related Notes

- [[agents]]