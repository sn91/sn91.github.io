---
layout: page
title: RAG and LLM Evaluation Project
description: Research on reducing hallucinations in mid-sized LLMs
img: 
importance: 1
category: Major
---

## Project Overview

Research Assistant (HiWi) project at TU Clausthal focused on building a **RAG-based factual reasoning pipeline** to analyze and reduce hallucinations in mid-sized (8B) Large Language Models.

**Duration**: September 2025 – December 2025  
**Institution**: TU Clausthal

## Research Goals

1. **Hallucination Analysis**: Understanding and quantifying hallucination patterns in 8B-parameter LLMs
2. **RAG Pipeline Development**: Building retrieval-augmented generation systems for factual grounding
3. **Benchmark Development**: Creating custom evaluation benchmarks for factual accuracy
4. **Knowledge Editing**: Experimenting with techniques for trustworthy LLM behavior

## Methodology

### LLM Evaluation
- Comparing two 8B-parameter LLMs using custom benchmarks
- Measuring embedding similarity metrics
- Analyzing retrieval latency and performance

### RAG Pipeline
- Implementing structured retrieval for factual grounding
- Testing different chunking and embedding strategies
- Optimizing retrieval-generation interaction

### Knowledge Editing
- Experimenting with techniques to correct factual errors
- Testing methods for injecting new knowledge
- Evaluating impact on model behavior

## Technical Stack

- **LLMs**: 8B-parameter models (Llama, Mistral variants)
- **Embeddings**: Sentence transformers, custom embeddings
- **Vector Store**: FAISS, Chroma
- **Framework**: LangChain, Hugging Face Transformers
- **Evaluation**: Custom benchmarks, RAGAS metrics
- **Infrastructure**: GPU computing, Python

## Key Research Questions

1. How do different retrieval strategies affect hallucination rates?
2. Can structured retrieval methods outperform naive RAG approaches?
3. What is the trade-off between retrieval latency and factual accuracy?
4. How effective are knowledge editing techniques in reducing hallucinations?

## Expected Outcomes

- Quantitative analysis of hallucination patterns in 8B LLMs
- Improved RAG pipeline designs for factual reasoning
- Evaluation framework for LLM trustworthiness
- Insights into knowledge editing effectiveness

