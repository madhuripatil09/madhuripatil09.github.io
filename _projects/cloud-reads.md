---
title: "CloudReads — Cloud-Based Digital Library"
date: 2023-10-01
layout: single
author_profile: true
permalink: /projects/cloud-reads/
excerpt: "Scalable cloud-native digital library on AWS with RDS-backed MySQL, multi-user access, and content customization."
header:
  teaser: /assets/images/Picture1.jpg
  overlay_color: "#1a1a2e"
  overlay_filter: 0.7
tags: [Java, Spring Boot, AWS, MySQL, Cloud]
toc: true
toc_label: "Sections"
---

<div class="badges-row">
  <span class="badge badge-cloud">AWS</span>
  <span class="badge badge-fs">Full Stack</span>
</div>

## Overview

CloudReads is a **scalable cloud-native digital library** deployed on AWS. It provides multi-user access to digital content with personalization features, backed by Amazon RDS for reliable data persistence.

## Key Features

- **Multi-user access** — role-based content access and user management
- **AWS S3 integration** — cloud storage for digital content
- **RDS-backed database** — Amazon RDS (MySQL) for scalable persistence
- **Content customization** — user preferences, reading history, recommendations
- **Scalable backend** — Spring Boot services designed for horizontal scaling on AWS

## Architecture

```
Client (Browser)
        ↓
Spring Boot Application (AWS EC2)
        ↓
Amazon RDS (MySQL) + AWS S3 (content storage)
```

## Tech Stack

| Layer | Technologies |
|---|---|
| Backend | Java · Spring Boot |
| Database | MySQL · Amazon RDS |
| Cloud | AWS EC2 · AWS S3 · AWS RDS |
| Frontend | HTML · CSS · JavaScript |
