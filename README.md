<div align="center">

# Hey, I'm Saksham Kaushik 👋

**I build software for real-world problems: civic issue resolution and rooftop solar planning.**

B.Tech CSE @ GL Bajaj Institute of Technology & Management • BS Data Science @ IIT Madras

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Saksham%20Kaushik-0A66C2?style=for-the-badge\&logo=linkedin)](https://www.linkedin.com/in/saksham-kaushik-942706369/)
[![LeetCode](https://img.shields.io/badge/LeetCode-400%2B%20Solved-FFA116?style=for-the-badge\&logo=leetcode)](https://leetcode.com/u/skaushik_0987/)
[![Email](https://img.shields.io/badge/Email-kaushiksaksham27%40gmail.com-D14836?style=for-the-badge\&logo=gmail\&logoColor=white)](mailto:kaushiksaksham27@gmail.com)

</div>

---

## 🚀 Featured Projects

### 🏙️ [NagrikSetu](https://github.com/saksham6541/nagriksetu): civic issue resolution, end to end

> Bridging citizens and municipal authorities through transparent, AI-assisted issue resolution.

Citizens report local problems (potholes, streetlights, garbage, water leaks) with location and photos, build consensus through upvotes, and track resolution in real time. Officers and field workers get role-based dashboards to triage, assign, verify and close the work.

* 🔐 **Role-based auth:** citizens (phone + OTP), officers and workers (email + password), JWT with `CITIZEN | OFFICER | WORKER | ADMIN` guards
* 🤖 **AI-assisted triage:** classification and routing suggestions via Google Gemini, with a deterministic local fallback when no API key is set
* 📍 **Geospatial duplicate hints:** bounding-box queries on indexed lat/lng
* 🔄 **Validated workflow:** assignment state machine (accept → in-progress → completed) with before/after evidence uploads
* 🧪 **Tested:** Vitest + Supertest covering auth, role checks, Zod validation, vote dedup and the AI fallback
* 🏗️ **Clean backend:** Express services, Zod schemas, Pino logging, Prisma transactions, rate limiting

**Stack:** TypeScript • React 19 • Vite • Tailwind CSS 4 • Express • Prisma • SQLite (PostgreSQL-ready) • Zod • Gemini

<p align="center">
  <img src="https://raw.githubusercontent.com/saksham6541/nagriksetu/main/screenshots/dashboard.png" width="48%" alt="NagrikSetu dashboard" />
  <img src="https://raw.githubusercontent.com/saksham6541/nagriksetu/main/screenshots/report-issue.png" width="48%" alt="Report an issue" />
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/saksham6541/nagriksetu/main/screenshots/officer-dashboard.png" width="48%" alt="Officer dashboard" />
  <img src="https://raw.githubusercontent.com/saksham6541/nagriksetu/main/screenshots/worker-dashboard.png" width="48%" alt="Worker dashboard" />
</p>

[![Repo](https://img.shields.io/badge/View%20Repository-NagrikSetu-00D4FF?style=for-the-badge\&logo=github)](https://github.com/saksham6541/nagriksetu)

---

### ☀️ [SIGNIX](https://github.com/saksham6541/SIGNIX): rooftop solar planning & estimation for India

A Flask-based planning tool: locate a property, draw the roof and obstructions on a map, and get indicative generation, savings and payback, then export PDF reports.

* 🗺️ **Map-based roof planning:** Leaflet roof editor with obstruction marking and geometry-aware sizing
* ☀️ **Irradiance and generation:** NASA POWER and PVGIS providers with fallback behaviour
* 💰 **Financial planning:** system cost, savings, payback and indicative PM Surya Ghar subsidy
* 🏠🏢 **Residential and Commercial tracks:** separate calculation policies, validated server-side
* 📄 **PDF reports:** a homeowner summary and a detailed technical report (WeasyPrint with ReportLab fallback)
* 🌐 **Bilingual:** English and Hindi, including Devanagari fonts in the PDFs
* 💾 **Saved estimates and scenario comparison**, plus a 3D rooftop visualization workflow
* 🧪 **Regression-tested** across estimation, auth, calculation tracks, reports and rooftop geometry

**Stack:** Python • Flask • Jinja2 • SQLAlchemy • Leaflet • pvlib • WeasyPrint • Docker

<p align="center">
  <img src="https://raw.githubusercontent.com/saksham6541/SIGNIX/main/app/static/images/signix-logo-full.png" width="40%" alt="SIGNIX" />
</p>

[![Repo](https://img.shields.io/badge/View%20Repository-SIGNIX-00D4FF?style=for-the-badge\&logo=github)](https://github.com/saksham6541/SIGNIX)

---

## 🧩 More Projects

| Project | What it is | Stack |
| ------- | ---------- | ----- |
| [**DataForge AI**](https://github.com/saksham6541/Code_cubicle) | AI-powered data intelligence platform (hackathon) | AI • Data |
| **Commodity Derivatives Intelligence** | MCX gold futures analysis (Hack in Hills '26) | Data • Analytics |
| [**Distributed File Upload**](https://github.com/saksham6541/distributed-file-upload) | Chunked, resumable uploads with verification | TypeScript • Express • React • MongoDB |
| [**cjson-rs**](https://github.com/saksham6541/cjson-rs) | Rust port of the cJSON C library | Rust |

---

## 🛠️ Tech I've Shipped With

<img src="https://skillicons.dev/icons?i=ts,react,vite,tailwind,nodejs,express,python,flask,prisma,sqlite,mongodb,docker,rust,git" />

---

## 🧠 DSA

400+ LeetCode problems, with a focus on patterns and time/space complexity rather than the count.

---

<div align="center">

*Currently learning: PostgreSQL in depth, Docker & CI/CD, distributed systems.*

<img src="https://komarev.com/ghpvc/?username=saksham6541&label=Profile%20Views&color=00D4FF&style=for-the-badge" />

</div>
