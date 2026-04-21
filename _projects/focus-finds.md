---
title: "Focus Finds — Full-Stack E-Commerce Platform"
date: 2024-01-01
layout: single
author_profile: true
permalink: /projects/focus-finds/
excerpt: "Production-style full-stack e-commerce with Spring Boot + React. Authentication, catalog, order processing, and admin workflows."
header:
  teaser: /assets/images/Picture1.jpg
  overlay_color: "#1a1a2e"
  overlay_filter: 0.7
tags: [Java, Spring Boot, React, MySQL, REST APIs]
toc: true
toc_label: "Sections"
---

<div class="badges-row">
  <span class="badge badge-fs">Full Stack</span>
  <span class="badge badge-cloud">Spring Boot</span>
</div>

## Overview

Focus Finds is a **production-style full-stack e-commerce application** built with a Spring Boot backend and React frontend, implementing the complete shopping experience from authentication to order fulfillment.

## Key Features

- **User Authentication** — JWT-based login/registration with role-based access (customer / admin)
- **Product Catalog** — category browsing, search, filtering, product detail pages
- **Shopping Cart & Orders** — cart management, checkout flow, order history
- **Admin Dashboard** — product management, order processing, inventory tracking
- **Clean REST API** — RESTful endpoints following clean architecture principles

## Architecture

```
React Frontend (SPA)
        ↓
Spring Boot REST API (Controller → Service → Repository)
        ↓
MySQL Database
```

## Tech Stack

| Layer | Technologies |
|---|---|
| Backend | Java · Spring Boot · REST APIs |
| Frontend | React · HTML · CSS · JavaScript |
| Database | MySQL |
| Version Control | Git · GitHub |
