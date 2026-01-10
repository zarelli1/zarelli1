# Hi there, I'm Leonardo Zarelli 👋

> **Full Stack Analytics Engineer** bridging the gap between Software Engineering, Data Intelligence, and Process Automation.

I design scalable systems that turn raw data into actionable business insights. My focus is on **clean architecture**, **automated workflows**, and **intuitive interfaces**.

---

## 🛠️ The Tech Ecosystem

My toolbox is optimized for performance and scalability:

| Domain | Stack |
| :--- | :--- |
| **Frontend & UI** | React (Next.js/Vite), TailwindCSS, ShadcnUI, Recharts |
| **Backend & API** | Node.js (NestJS), REST Architecture, Supabase |
| **Data & Logic** | PostgreSQL, SQL Modeling, Business Intelligence Logic |
| **Ops & Auto** | n8n (Workflow Automation), Docker, AI Agents |

---

## 💼 Featured Architecture: Social CRM Engine

**Role:** Lead Analytics Engineer (Stealth Startup)

I architected the core data engine to solve a critical blindness in sales operations.

* **The Challenge:** The sales team lacked real-time visibility on **CAC** (Customer Acquisition Cost) and **LTV** (Lifetime Value), leading to inefficient ad spend.
* **The Solution:** A full-stack ecosystem that ingests leads, enriches data, and visualizes ROI in real-time.

```mermaid
graph TD
    A[📱 Social Leads] -->|Raw Data| B(⚡ n8n Automation Workflows)
    B -->|Enriched Lead| C{⚙️ NestJS Core API}
    C -->|Store Transaction| D[(🗄️ PostgreSQL)]
    C -->|Calculate LTV/CAC| E[📊 Next.js Analytics Dashboard]
    
    style B fill:#ff9f43,stroke:#333,stroke-width:2px,color:#fff
    style C fill:#ee5253,stroke:#333,stroke-width:2px,color:#fff
    style E fill:#2e86de,stroke:#333,stroke-width:2px,color:#fff
