---
layout: page
title: LLM-Based Revision System for CS
description: RAG pipeline with GPT-J and FAISS for intelligent study assistance
img: 
importance: 1
category: Major
---

## Project Overview

Built a revision assistant using a **RAG (Retrieval-Augmented Generation) pipeline** with GPT-J and FAISS vector database to help students prepare for computer science exams.

## Key Features

- **Context-aware retrieval**: Indexed all course notes and reference materials for intelligent document retrieval
- **FAISS vector database**: Efficient similarity search across large document collections
- **LangChain orchestration**: Applied fine-tuned prompts for accurate, domain-specific answers
- **Hallucination reduction**: Implemented techniques to minimize incorrect information in responses
- **Interactive exam preparation**: Enabled efficient summarization and Q&A for study sessions

## Technical Stack

- **Language Model**: GPT-J (6B parameters)
- **Vector Store**: FAISS
- **Orchestration**: LangChain
- **Embeddings**: Sentence transformers
- **Backend**: Python

## Architecture

The system follows a standard RAG architecture:

1. **Document Ingestion**: Course materials are chunked and embedded
2. **Vector Storage**: Embeddings are stored in FAISS for fast retrieval
3. **Query Processing**: User questions are embedded and similar documents are retrieved
4. **Generation**: Retrieved context is passed to GPT-J with custom prompts
5. **Response**: Domain-specific answers are generated with minimal hallucination

## Results

- Achieved significant reduction in hallucinated content compared to vanilla LLM responses
- Enabled faster revision cycles for students
- Provided accurate, source-backed answers to complex CS questions

