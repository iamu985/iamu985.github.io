---
title: Talent Radar
stack: [Python, Langchain, LLM, FastAPI]
source_url: https://github.com/iamu985/talent-radar
featured_image: /assets/imgs/projects/talent_radar/talent-radar.png
description: AI recruitment automation tool that helps businesses find the best candidates in minutes, not weeks.
tag: [ai, automation, personal]
class: projects
is_live: true
---
*A self-reliant tool for navigating modern recruitment.*  
**Version:** 1.0  
**Date:** April 2025

---

## 1. Introduction

### 1.1 Purpose  
Hiring is repetitive. Talent Radar handles the monotony. It reads resumes, learns from job descriptions, matches intent, and prepares interviews. It works quietly and efficiently—designed to shrink time and surface relevance.

![Talent Radar](/assets/imgs/projects/talent_radar/talent-radar.png "Optional title")

### 1.2 Scope  

**Included:**  
- Parsing resumes, extracting signal from noise.  
- Matching human potential to job descriptions using vector mathematics.  
- Generating questions for interviews.  
- Updating real-time status using Redis.  
- Connecting with ecosystems like Odoo, WhatsApp, and email.<br><br>
**Not Included:**  
- Payroll.  
- Onboarding.  
- Multi-user dashboards.

### 1.3 Stack  

| Component      | Technology                        |
|--------------- |-----------------------------------|
| Backend        | FastAPI (AI), Django (Admin)      |
| Storage        | PostgreSQL, Pinecone/Milvus       |
| Queue          | Redis                             |
| Intelligence   | LangChain, OpenAI Embeddings      |
| Integrations   | Odoo CRM, Twilio (WhatsApp)       |

---

## 2. Shape of the System

### 2.1 Overview

![Talent Radar](/assets/imgs/projects/talent_radar/graph-dark.svg "Graph")
