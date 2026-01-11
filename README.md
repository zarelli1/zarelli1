<div align="center">

# Hi there, I'm Leonardo Zarelli 👋

> **Full Stack Analytics Engineer** | Building high-performance transactional systems.

I specialize in **complex business logic**, **data integrity**, and **real-time performance**.

<br>

<img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white" />
<img src="https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white" />
<img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" />
<img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" />

</div>

---

### 🏗️ The Architecture

My systems are designed for scalability, security (JWT), and real-time performance (WebSockets).

```mermaid
graph TD
    subgraph Client ["🖥️ Client Layer"]
        UI[Next.js / Vite]
        State[React Query]
    end

    subgraph API ["⚙️ Backend Layer"]
        Nest[NestJS API]
        Socket[WebSocket Gateway]
    end

    subgraph Data ["🗄️ Persistence"]
        DB[(PostgreSQL)]
        Supa[(Supabase)]
    end

    UI <-->|REST / Secure JSON| Nest
    Nest <-->|ORM| DB
    Nest <-->|Auth| Supa
    Socket -.->|Real-time| UI

    style Client fill:#f8f9fa,stroke:#333,color:#000
    style API fill:#ffeaa7,stroke:#333,color:#000
    style Data fill:#81ecec,stroke:#333,color:#000
```
---

Project,Tech Highlights
1. Social CRM Engine(Stealth Startup),Stack: NestJS WebSocketsSales automation ecosystem with JWT Guards and real-time lead distribution.
2. Ótica SZ POS(Retail System),"Stack: React PostgreSQLSolved complex ""Lenses vs. Frames"" inventory logic and scheduled reporting."
3. Carimbo SZ(Loyalty SaaS),Stack: Supabase SQLRetention platform with complex SQL aggregations and legacy data normalization.
---
<div align="center">
  <br>
  <h3>Let's Connect & Build</h3>
  <a href="https://www.linkedin.com/in/leonardo-zarelli/" target="_blank">LinkedIn</a>
  &nbsp; • &nbsp;
  <a href="https://leonardozarelli.substack.com" target="_blank">Substack</a>
  &nbsp; • &nbsp;
  <a href="https://www.youtube.com/@Leonardo_Zarelli" target="_blank">YouTube</a>
  <br><br>
</div>
