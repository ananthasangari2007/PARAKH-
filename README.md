# SIH26031 - Quality assessment and grading of onions are often subjective and vary across procurement centers, resulting in disputes and inconsistencies.

[![Smart India Hackathon 2026](https://img.shields.io/badge/SIH-2026-blue.svg)](https://sih.gov.in)
[![Category](https://img.shields.io/badge/Category-Software-emerald.svg)](https://sih.gov.in)
[![Ministry / Org](https://img.shields.io/badge/Organization-Ministry%20of%20Consumer%20Affairs,%20Food%20&amp;%20Public%20Distribution-indigo.svg)]()
[![Theme](https://img.shields.io/badge/Theme-Smart%20Automation-purple.svg)]()
[![Domain](https://img.shields.io/badge/Domain-Landslide%20&%20Slope%20Stability%20GIS-orange.svg)]()

---

## 🎯 Problem Statement Overview
- **Problem Statement ID:** `SIH26031`
- **Title:** Quality assessment and grading of onions are often subjective and vary across procurement centers, resulting in disputes and inconsistencies.
- **Sponsoring Organization:** Ministry of Consumer Affairs, Food & Public Distribution
- **Department:** Department of Consumer Affairs (DoCA)
- **Category:** Software
- **Theme:** Smart Automation

### 📖 Official Description
Expected Solution: Develop an AI-based mobile application that:• Uses image processing to assess onion quality.• Identifies damaged, rotten, sprouted, or undersized onions.• Estimates Grade A and URS percentages.• Generates a digital quality report instantly.• Reduces human bias and improves transparency.

---

## 💡 Proposed Solution Architecture
Our team has engineered a comprehensive, production-ready solution tailored specifically for **Ministry of Consumer Affairs, Food & Public Distribution**:
1. **Interactive Mission Control Dashboard (`project/index.html`):** Glassmorphic dark-mode web application featuring real-time Chart.js telemetry, interactive parameter tuning, automated simulation triggers, and exportable audit logs.
2. **FastAPI Microservice Engine (`project/app.py`):** High-throughput Python REST backend with Pydantic v2 validation, domain-specific AI anomaly scoring, cryptographic audit logs, and OpenAPI Swagger documentation.
3. **Comprehensive Technical Whitepaper (`project/solution.md`):** Complete architectural breakdown, mathematical formulations, PostgreSQL + PostGIS DDL schemas, and deployment topologies.
4. **Automated Test Suite (`project/test_app.py`):** Built-in unit and integration tests verifying all REST endpoints.
5. **Turnkey Containerization (`project/Dockerfile` & `project/docker-compose.yml`):** Ready for one-command deployment on Docker / Kubernetes.

---

## 🚀 Quick Start Guide

### Option 1: Instant Browser Demo (Zero Setup)
Simply open `project/index.html` in any modern web browser or serve it locally:
```bash
cd "SIH26031 - Quality assessment and grading of onions are often subjective and vary/project"
python -m http.server 8080
```
Open [http://localhost:8080](http://localhost:8080) to access the command center.

### Option 2: Run Full Python FastAPI Microservice
```bash
cd "SIH26031 - Quality assessment and grading of onions are often subjective and vary/project"
pip install -r requirements.txt
python app.py
```
- API Server: [http://127.0.0.1:8000](http://127.0.0.1:8000)
- Interactive OpenAPI Docs: [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)

### Option 3: Run Automated Tests
```bash
cd "SIH26031 - Quality assessment and grading of onions are often subjective and vary/project"
pytest test_app.py -v
```

---

## 📂 Project Repository Structure
```plaintext
SIH26031 - Quality assessment and grading of onions are often subjective and vary/
├── README.md                           # Main problem statement pitch & guide
├── problem_statement.json              # Official SIH 2026 metadata
└── project/
    ├── index.html                      # Interactive Dark-Mode Glassmorphism Web App
    ├── app.py                          # FastAPI REST API Microservice
    ├── test_app.py                     # Pytest automated test suite
    ├── solution.md                     # Deep-dive 8-section technical whitepaper
    ├── requirements.txt                # Python backend dependencies
    ├── Dockerfile                      # Production Docker container definition
    ├── docker-compose.yml              # Multi-container orchestration
    └── README.md                       # Project execution manual
```
