---
title: "Resume Navigator — AI-Driven Resume Analysis"
date: 2024-06-01
layout: single
author_profile: true
permalink: /projects/resume-navigator-chatbot/
excerpt: "LLM-powered resume screening using RAG + FAISS. Reduced shortlisting effort by 60%, improved matching accuracy by 50%."
header:
  teaser: /assets/images/Picture1.jpg
  overlay_color: "#1a1a2e"
  overlay_filter: 0.7
tags: [Python, LLMs, NLP, RAG, FAISS, Flask, AI]
toc: true
toc_label: "Sections"
---

<div class="badges-row">
  <span class="badge badge-ai">AI / LLM</span>
  <span class="badge badge-ml">Deep Learning</span>
  <span class="badge badge-cloud">Flask API</span>
</div>

## Overview

Resume Navigator is an **AI-powered resume screening system** that leverages Large Language Models, semantic embeddings, and vector similarity search to automate and dramatically improve the candidate shortlisting process.

- **60%** reduction in manual shortlisting effort
- **50%** improvement in candidate-to-job matching accuracy

## Key Features

- **LLM-based semantic analysis** — extracts skills, experience, and context from free-form resume text
- **RAG + FAISS pipeline** — generates embeddings and runs fast semantic similarity search against job descriptions
- **NLP preprocessing** — tokenization, entity recognition, skill normalization
- **Flask REST API backend** — clean API interface for integration with HR tools
- **Containerized deployment** — packaged as a Docker web application

## Architecture

```
Resume Upload (PDF / Text)
        ↓
NLP Preprocessing Pipeline
        ↓
Embedding Generation (LLM)
        ↓
FAISS Vector Store ←→ Job Description Embeddings
        ↓
Semantic Similarity Scoring
        ↓
Ranked Candidate Shortlist
```

## Tech Stack

| Layer | Technologies |
|---|---|
| AI / ML | LLMs · RAG · FAISS · NLP · Embeddings |
| Backend | Python · Flask · REST API |
| Frontend | HTML · CSS · JavaScript |
| Infrastructure | Docker |
