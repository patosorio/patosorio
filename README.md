# Hi, I'm Patricia 

I'm a Python developer and backend Engineer specialising in business process automation. 
[www.patosorio.com](https://patosorio-website.web.app/)

---

## Featured Project

### Green Bridge — GMP SaaS ERP (FastAPI + Next.js + PostgreSQL + GCP)

🔒 **Private repository** — this platform handles pharmaceutical-grade regulatory and cultivation data, so the codebase isn't public. **[Reach out for a demo](mailto:patosorio.88@gmail.com)**.

Sole technical architect and developer of a multi-tenant SaaS ERP platform for GMP-regulated medical cannabis cultivation, processing, and export to Germany and the Netherlands, built toward EU GMP Annex 11 certification.

- **Backend**: FastAPI (async) + SQLAlchemy 2.0 (async) + PostgreSQL + pgvector  
- **Frontend**: Next.js 15 (App Router) + TanStack Query v5  
- **Infra**: GCP (Cloud Run, Cloud SQL, Secret Manager)  
- **Compliance**: GAMP 5, EU GMP Annex 11, 21 CFR Part 11 — full validation documentation suite (URS through IQ/OQ/PQ)  
- **Scope**: Full data model, API design, and security architecture for a validated, multi-tenant pharma-grade platform  

---

## AI Projects

### [Nouri — AI Food Advisor & Meal Planner (FastAPI + Next.js + Claude)](https://github.com/patosorio/nouri)

A personalised AI meal planner for plant-based eaters. Set your diet, goals, and preferences — the app generates a 7-day meal plan, tracks your pantry, and produces a shopping list for what's missing. Save any AI-generated meal you love with one click; future plans get smarter every time you do.

- **Backend**: FastAPI + SQLAlchemy 2.0 (async) + PostgreSQL (Supabase)
- **Frontend**: Next.js 15 (App Router)
- **AI Models**: Claude Sonnet 4.6 (agent + recipe generation) · Claude Haiku 3.5 (structured tasks)
- **Features**:  
  - Conversational meal planning via an agentic tool-use loop
  - Deterministic macro, exclusion, and protein variety validation
  - Recipe generation, substitution, and semantic search (pgvector + Voyage AI)
  - Async weekly plan generation with real-time notifications (Supabase Realtime)
  - Pantry tracking + auto-generated, diff'd shopping lists
- **Auth**: Supabase Auth (JWT RS256)  
- **Infra**: GCP Cloud Run, Supabase

---

### [Project Brief AI Assistant (FastAPI + Gemini API)](https://github.com/patosorio/scaling-doodle)

A Python API that transforms project documents into business-friendly briefs and enables semantic search using Google's Gemini File Search API.

- **Backend**: FastAPI  
- **AI Model**: Google Gemini 2.5 Flash  
- **Features**:  
  - File upload and automatic project brief generation  
  - Semantic search over project documents  
  - RAG-style architecture with File Search Store  
- **Architecture**: Modular separation of concerns (API layer, Gemini client, prompts)  
- **Tech Stack**: FastAPI, Python 3.10+, Gemini API, Pydantic, Uvicorn  

---

### [Lead Enrichment & Scoring System (Python + OpenAI)](https://github.com/patosorio/super-duper-guacamole)

An AI-powered lead qualification pipeline built for a GTM/sales use case — extracts structured insight from raw lead notes, scores lead quality, and routes leads to the right team automatically.

- **Language**: Python  
- **AI Model**: OpenAI API (structured outputs)  
- **Features**:  
  - LLM extraction of industry, company size, and buyer intent from unstructured notes  
  - Points-based scoring engine (0–100) weighted by industry relevance, company size, and intent clarity  
  - Automatic routing: 70+ score to sales, others to marketing nurture  
  - Rule-based fallback (~70% accuracy) keeps the pipeline working without API access  
  - Batch processing — ~100 leads in 20 seconds via thread pooling  
- **Tech Stack**: Python, OpenAI API, Pydantic, ThreadPoolExecutor, Tenacity  

---

## Data Visualization & BI Projects

### [Integralta Analytics v2 — Financial Analytics Platform (Next.js + FastAPI + Supabase)](https://github.com/patosorio/finance-dashboard)

Financial analytics platform for an industrial laundry company, syncing ERP data from Holded into Postgres for real-time BI reporting and an embedded AI financial advisor.

- **Backend**: FastAPI (async, Python 3.12) + SQLAlchemy 2.0 + Alembic  
- **Data Source**: Holded ERP API (invoices, purchases, payroll, taxes, ledger)  
- **Database**: Postgres (Supabase, with Auth + Row Level Security)  
- **Frontend**: Next.js 15 (App Router) + TypeScript + Tailwind + shadcn/ui + TanStack Query  
- **AI**: Anthropic Claude (native SDK, tool-use loop) — read-only financial advisor, never computes on its own  
- **Features**:  
  - Scheduled Holded → Postgres sync engine  
  - Deterministic finance engine (€/kg cost allocation, client profitability, 13-week cashflow forecast)  
  - Editable business rules (cost pools, weights, margins) as config tables, not hardcoded constants  
  - Pydantic validation, structured logging, 100% unit-tested engine logic

---

## Web Applications

### [Pharma Genetics ERP (Django + Next.js)](https://github.com/patosorio/pharma-genetics-erp)

ERP for a GACP-certified genetics cultivation business (Fenopharm.eu).

- **Frontend**: Next.js (Admin UI) with Firebase Auth  
- **Backend**: Django 5 + Django Admin (+ DRF), PostgreSQL (Cloud SQL)  
- **Modules**: Core, Genetics, Cultivation, Inventory, Sales, Purchasing, HR, Accounting  
- **Features**: Real-time CRUD operations, normalized schema with foreign keys, audit trails, soft deletes, and role-based access 


### [Artists Bookings (Next.js + Django)](https://github.com/patosorio/Artist-bookings)

Full-stack project to manage bookings for an artist agency.  

This app includes multi-tenancy support, allowing different agencies to manage their own data in isolation. The challenge was designing a scalable backend that keeps each tenant’s users, bookings, and artist data separate while using shared infrastructure. I implemented this with a clean Django architecture that organizes models and routes per tenant context.

- **Frontend**: Built with Next.js using Vercel’s `v0` AI-powered generator  
- **Backend**: Django REST Framework  
- **Hosting**: Frontend on Firebase Hosting, Backend on Google Cloud Run  
- **Authentication**: Firebase Authentication
- **Storage**: Cloud Storage 
- **Database**: PostgreSQL (Cloud SQL)  

### [Smart Budget (Next.js + FastAPI)](https://github.com/patosorio/expenses-tracker)

**[Repository](https://github.com/patosorio/expenses-tracker)**

This project combines Next.js frontend with a FastAPI backend, offering a secure and scalable solution for managing expenses, budget forecast with ai assistant integrated. While leveraging Firebase for authentication, the application uses a custom backend with SQL database for data persistence and business logic.

- **Frontend**: Built with Next.js using Vercel’s `v0` AI-powered generator
- **Backend:**: FastAPI with SQLAlchemy
- **Hosting**: Firebase (Frontend) / Backend in Cloud Run (GCP)  
- **Authentication**: Firebase Authentication 
- **Database**: SQL database with Alembic migrations

---

## Websites

### Pharma Genetics Website (Next.js + Firebase + Firestore)  
[Repository](https://github.com/patosorio/Pharma-Genetics-Website) • [Website](http://fenopharm.eu)

A custom-built website for a law firm with an integrated **admin panel** that allows site users to manage content dynamically.  

- **Frontend**: Next.js  
- **Backend/Hosting**: Firebase + Firestore  
- **Features**: Admin panel for content management 

### Law Firm Website (Next.js + Firebase + Firestore)  
[Repository](https://github.com/patosorio/law-firm-website) • [Website](https://abogado-gentile.web.app/)

A custom-built website for a law firm with an integrated **admin panel** that allows site users to manage content dynamically.  

- **Frontend**: Next.js  
- **Backend/Hosting**: Firebase + Firestore  
- **Features**: Admin panel for content management  

---

### Midnight Escales (Next.js + Firebase + Firestore)  
[Repository](https://github.com/patosorio/midnight-escale) • [Website](https://midnight-escale.web.app/)

A website for **luxury Morocco tours** with an integrated **admin panel** for the site owner to easily add itineraries and curated experiences.  

- **Frontend**: Next.js  
- **Backend/Hosting**: Firebase + Firestore  
- **Features**: Admin panel for itinerary and experience management

---
## Business Automations

I build Python-based automations focused on real-world business tasks.  
Check one of my automation projects here:  
**[Airtable](https://github.com/patosorio/airtable-drive-sync)**  
Other automation:  
**[Google Drive API Automation & Sheets Sync](https://github.com/patosorio/drive-api-automation)**

---

## Contact
- [Website](https://www.patosorio.com)
- [LinkedIn](https://www.linkedin.com/in/patriciaosorio130194/)
- Email: patosorio.88@gmail.com

Currently learning cybersecurity, while I'm not a professional in the field yet, I'm actively building my skills.
