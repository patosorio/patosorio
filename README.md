# Hi, I'm Patricia 

I'm a Python developer specializing in business process automation. Currently learning cybersecurity, while I'm not a professional in the field yet, I'm actively building my skills.
[www.patosorio.com](https://patosorio-website.web.app/)

---

## AI Projects

### [Nouri — AI Food Advisor & Meal Planner (FastAPI + Next.js + Claude)](https://github.com/patosorio/nouri)

A personalised AI meal planner for plant-based eaters. Set your diet, goals, and preferences — the app generates a 7-day meal plan, tracks your pantry, and produces a shopping list for what's missing. Save any AI-generated meal you love with one click; future plans get smarter every time you do.

- **Backend**: FastAPI + SQLAlchemy (async) + PostgreSQL  
- **Frontend**: Next.js 15  
- **AI Models**: Claude Sonnet (meal plan generation)  
- **Features**:  
  - 7-day personalised meal plan generation  
  - Pantry tracking + auto-generated shopping lists  
  - Recipe bookmarking with semantic search (pgvector)  
  - Calendar scheduling with Firestore sync  
  - Taste profile that improves with every interaction  
- **Auth**: Firebase Authentication (Google OAuth)  
- **Infra**: Cloud Run, Cloud SQL, Firebase Hosting  

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

## Data Visualization & BI Projects

### [Pharma Genetics Business Plan Dashboard API (FastAPI + Dash Plotly)](https://github.com/patosorio/pharma-genetics-bplan)

API and dashboard pipeline for **Pharma Genetics**, syncing financial data from Google Sheets into SQL for real-time business intelligence reporting.

- **Backend**: FastAPI + SQLAlchemy + Alembic  
- **Data Source**: Google Sheets API  
- **Database**: SQLite (Local)  
- **Visualization**: Dash & Plotly (financial and operations dashboards)  
- **Features**:  
  - Automated Google Sheets sync  
  - Hierarchical expense categories  
  - Financial summaries (income, expenses, net position)  
  - Exception handling, Pydantic validation, logging  

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
