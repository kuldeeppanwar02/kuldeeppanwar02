<!-- Header -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f6b63,100:2563eb&height=160&section=header&text=Kuldeep%20Panwar&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Building%20real%20systems%20for%20real%20people&descAlignY=58&descSize=16" width="100%"/>

</div>

---

## Who I am

I open things to understand how they work.

Started in 2nd standard — machines, systems, anything mechanical. That curiosity never stopped. Now I build software the same way: go deep, understand every layer, don't stop until it actually works.

I don't talk about what I'm building. I ship it, deploy it, and let people use it. The footer of three production websites in Rajasthan says:

> *"Designed & Developed by Kuldeep Panwar"*

**That's my communication strategy.**

---

## What I've shipped — in production, right now

<table>
<tr>
<td width="50%" valign="top">

### 🏥 Panwar Health Care
**[drsattarampanwar.com](https://drsattarampanwar.com)**

Hindi-first clinic queue PWA. 3 departments, 1 codebase. Patients scan a QR code at the door, get a numbered token, track their queue position from their phone — no paper, no calls.

**100+ patients served daily.** Production since 2026.

`Next.js 15` · `Supabase` · `IndexedDB` · `PWA`

</td>
<td width="50%" valign="top">

### 🏪 ScanMart Partner
**[scanmart-app.vercel.app](https://scanmart-app.vercel.app)**

Pharmacy & retail ERP SaaS. Full POS terminal, batch/expiry (FEFO) tracking, H1 narcotics register, GST filing, khata CRM, multi-store switching, offline billing with IndexedDB replay.

13+ versioned SQL migrations. Atomic stock decrements via PostgreSQL RPC with cross-store RLS.

`Next.js 16` · `TypeScript` · `Supabase` · `Tailwind CSS 4`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏥 Renwal Multi-Speciality Hospital
**[Renwal Hospital →](https://github.com/kuldeeppanwar02/Renwal-Multi-Speciality-Hospital)**

Production hospital platform. 5 specialist doctors, Ayushman Bharat + MAA Yojana empanelled. 3D-tilt doctor cards, animated stats counter, full modal system — deployed on **Cloudflare Workers** edge network.

Includes `Core_OS_Integration_Guide.md` — a blueprint for transplanting the clinic queue engine into multi-department hospital scale.

`HTML/CSS/JS` · `Cloudflare Workers` · `WebP`

</td>
<td width="50%" valign="top">

### ⚡ Chetnix Compute Network
**[Whitepaper + Prototype →](https://github.com/kuldeeppanwar02/chetnix)**

Independently designed a decentralized AI compute marketplace. Consumer GPU owners rent idle capacity to AI startups at 61% below AWS pricing. Settlement via Solana $CHX token.

Built an 11-factor adaptive scheduler with documented weight rationale, a 32-node global simulation (480 data points), proof-of-compute protocol with ed25519 signatures, and a full interactive specification for investors, engineers, miners, and AI startups.

*Same thesis as io.net (\$30M raised) — arrived at independently.*

`Electron` · `Rust` · `Solana` · `React Native` · `GoLang`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 TalentBridge — Resume Intelligence Engine
**[View Project →](https://github.com/kuldeeppanwar02/resume-screening-talentbridge)**

Hybrid NLP pipeline for resume screening. Rule-based scoring (60%) + TF-IDF cosine similarity (40%) = Hybrid Fit Score. Random Forest + Logistic Regression classifiers. 5,000 structured resume records. Custom dark-theme Streamlit dashboard.

`Python` · `NLTK` · `scikit-learn` · `Streamlit` · `pandas`

</td>
<td width="50%" valign="top">

### 🏫 Smart Digital Management
**[View Project →](https://github.com/kuldeeppanwar02/Smart-Digital-management)**

School ERP system. Attendance, exams, marks, fees, timetable, parent portal, admin dashboard. Full JWT auth, role-based access, MongoDB.

`Node.js` · `Express` · `React` · `Vite` · `MongoDB`

</td>
</tr>
</table>

---

## How I think about problems

```
Observe a problem nobody has solved well locally
        ↓
Understand every layer — from UI down to DB schema
        ↓
Build it. Deploy it. Watch real people use it.
        ↓
Iterate until there's nothing left to improve.
```

I built a healthcare queue OS and deployed it at a clinic in Jaisalmer.
I built a pharmacy ERP and made it work offline when the internet drops.
I designed a decentralized GPU network from first principles.

None of these were assignments. All of them were problems I saw and decided to fix.

---

## Tech I use daily

<div align="center">

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-black?logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38BDF8?logo=tailwind-css&logoColor=white)

**Backend & Data**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)

**AI / ML**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikit-learn&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-4B8BBE?logo=python&logoColor=white)
![GCP](https://img.shields.io/badge/GCP_Vertex_AI-4285F4?logo=google-cloud&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?logo=google&logoColor=white)

**Infrastructure**

![Vercel](https://img.shields.io/badge/Vercel-black?logo=vercel)
![Cloudflare](https://img.shields.io/badge/Cloudflare_Workers-F38020?logo=cloudflare&logoColor=white)
![Solana](https://img.shields.io/badge/Solana-9945FF?logo=solana&logoColor=white)

</div>

---

## Numbers that matter

<div align="center">

| | | |
|:---:|:---:|:---:|
| **100+** | **3** | **61%** |
| Patients using my software daily | Production deployments serving real users | Cost reduction vs AWS (Chetnix design) |
| | | |
| **13+** | **32** | **11** |
| SQL migration files in ScanMart | Simulated GPU nodes across 6 continents | Scheduler factors in Chetnix |

</div>

---

## GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=kuldeeppanwar02&show_icons=true&theme=dark&bg_color=0d1117&border_color=30363d&title_color=2563eb&icon_color=0f6b63&text_color=c9d1d9&hide_border=false&count_private=true" />
&nbsp;
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kuldeeppanwar02&layout=compact&theme=dark&bg_color=0d1117&border_color=30363d&title_color=2563eb&text_color=c9d1d9&hide_border=false" />

</div>

---

## What I'm focused on

- **Expanding ScanMart** — taking it from one pharmacy to a multi-tenant SaaS for Indian retail chains
- **Clinic OS at scale** — deploying the queue engine to Renwal Multi-Speciality Hospital
- **AI + healthcare** — combining Gemini Vision with the pharmacy import workflow (shelf → inventory, automated)
- **Chetnix Phase 1** — GoLang orchestrator + Rust scheduler microservice

---

## Reach me

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-kuldeeppanwar02-181717?logo=github)](https://github.com/kuldeeppanwar02)
[![Email](https://img.shields.io/badge/Email-panwarkuldeep256%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:panwarkuldeep256@gmail.com)

*I respond to opportunities, collaborations, and client projects.*
*Open to remote roles in full-stack, AI/ML, and healthcare tech.*

</div>

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563eb,100:0f6b63&height=100&section=footer" width="100%"/>
</div>
[README_github_profile.md](https://github.com/user-attachments/files/31609918/README_github_profile.md)
