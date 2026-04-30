
# Deliverable Copilot

AI-powered data deliverables copilot.

---

## Overview

Deliverable Copilot is a web-based prototype designed to help data teams (data scientists, AI engineers, consultants) **automatically generate professional project deliverables** from raw project sources.

The tool acts as an **AI-assisted workflow**, not just a text generator.

It enables users to:
- ingest project data (notebooks, scripts, datasets, documents)
- analyze and extract key information
- structure project knowledge
- generate high-quality deliverables (reports, presentations, summaries)
- track actions and ensure traceability

---

##  Key Features

###  Project Management
- Create and manage data projects
- Define client, project type, and deliverable type
- Organize work in a structured workflow

###  Data Ingestion
- Upload multiple sources:
  - Jupyter notebooks (`.ipynb`)
  - Python scripts (`.py`)
  - CSV / JSON data
  - PDF / Word / PowerPoint documents
- Simulated connectors (GitHub, SharePoint, Jira)

###  AI Analysis Pipeline
- Automatic extraction of:
  - objectives
  - datasets
  - models (XGBoost, Random Forest, LSTM)
  - metrics (F1-score, Accuracy, AUC)
- Step-by-step pipeline visualization

###  Structured View
- Clear representation of:
  - project summary
  - sources used
  - detected elements
  - missing information
- Improves transparency before generation

###  AI Writing Editor
- Section-based document generation:
  - Context
  - Methodology
  - Results
  - Recommendations
- Editable content (rich text style)
- Source traceability and confidence indicators
- AI suggestions and warnings

###  Templates Management
- Standard templates (technical report, executive summary, etc.)
- Client-specific templates (SNCF, Dalkia, Malakoff)
- Template import feature

###  Export & Versioning
- Export deliverables in multiple formats:
  - DOCX
  - PDF
  - PPTX
- Version tracking and history
- Restore and compare versions

###  History & Traceability
- Track all actions:
  - source imports
  - AI analysis
  - draft generation
  - exports
- Detailed activity logs

###  AI Chat Assistant
- Query project data in natural language
- Retrieve insights from sources
- Includes citations

###  Settings
- User profile
- AI configuration (tone, automation level)
- Connected tools

---

##  Tech Stack

This project is a **front-end prototype** built with:

- HTML
- CSS
- Vanilla JavaScript (no frameworks)

No backend or real AI is connected — all interactions are simulated for demonstration purposes.

---

https://zainebajra2.github.io/Livrables_IA/
