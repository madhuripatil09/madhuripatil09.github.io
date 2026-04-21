---
title: "Event Linker — AI-Powered Event Networking Platform"
date: 2024-03-01
layout: single
author_profile: true
permalink: /projects/event-linker/
excerpt: "QR-based event networking with AI-driven attendee similarity recommendations. 35% engagement lift, 50% faster check-ins."
header:
  teaser: /assets/images/Picture1.jpg
  overlay_color: "#1a1a2e"
  overlay_filter: 0.7
tags: [Python, Flask, React, MySQL, AWS, AI, OpenAI]
toc: true
toc_label: "Sections"
---

<div class="badges-row">
  <span class="badge badge-ai">AI / LLM</span>
  <span class="badge badge-cloud">AWS</span>
  <span class="badge badge-fs">Full Stack</span>
</div>

## Overview

Event Linker is a full-stack web platform combining **QR-code-based event entry**, **role-based access control**, and **AI-driven attendee recommendations** using OpenAI embeddings and cosine similarity.

- **35%** increase in networking engagement
- **50%** reduction in check-in time

## Key Features

**Authentication & Access Control** — Role-based: Organizer and Attendee. OTP-based password reset.

**Organizer Workflow** — Full event CRUD, auto-generate unique QR codes per event, upload to AWS S3, store metadata in AWS RDS.

**Attendee Networking** — Browse attendee directory, send/accept connection requests, view social profiles.

**AI Recommendation Engine** — Generates OpenAI embeddings for user bio + event descriptions, computes cosine similarity, applies category-based boosting to rank recommended events.

## Architecture

```
Client (HTML/CSS/JS)
        ↓
Flask App (Blueprints: user / organizer / attendee)
        ↓
AWS RDS (MySQL)  +  AWS S3 (media + QR codes)
        ↓
OpenAI Embeddings + Cosine Similarity Scoring
        ↓
Deployed on AWS EC2
```

## Tech Stack

| Layer | Technologies |
|---|---|
| Backend | Python · Flask (Blueprint architecture) |
| Frontend | HTML · CSS · JavaScript |
| Cloud | AWS EC2 · AWS RDS (MySQL) · AWS S3 |
| AI | OpenAI Embeddings API · Cosine Similarity |
