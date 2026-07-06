<h1 align="center">
  <img src="https://imgur.com/C7PX4kM.gif" width="30" height="30" alt="wave hand"/>  
  Hi, I'm <b>Anay Gupta</b>!
</h1>

<p align="center">
  <strong>Backend Software Engineer · AI Engineer</strong>
</p>

<p align="center">
  <a href="mailto:me@anaygupta.xyz"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white&color=2f2f2f"/></a>
  <a href="https://zssh.dev" target="_blank"><img src="https://img.shields.io/badge/Portfolio-4B0082?style=for-the-badge&logo=vercel&logoColor=white&color=1f1f1f"/></a>
  <a href="https://zssh.dev/resume" target="_blank"><img src="https://img.shields.io/badge/Resume-FFD700?style=for-the-badge&logo=readme&logoColor=000&color=2f2f2f"/></a>
  <a href="https://www.linkedin.com/in/anay-gupta-77b8831a1" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&color=1f1f1f"/></a>
  <a href="https://leetcode.com/u/anaygupta03/" target="_blank"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black&color=2f2f2f"/></a>
</p>

---

## Profile Summary

Backend Software Engineer building production-grade billing, gateway, and real-time AI infrastructure. Ex engineer on the **MegaLLM** backend — a multi-provider LLM gateway in front of 70+ models with idempotent Stripe/Razorpay/OxaPay billing, multi-tier caching, and full observability. Won **1st Position at the Govt. Pre Sabka AI Hackathon** for **Protego**, an AI-powered personal safety platform. Comfortable across TypeScript, Python, Hono, FastAPI, and cloud (AWS · Azure · GCP).

---

## Technical Skills

```
Languages          Python · TypeScript · JavaScript · C · SQL
Backend            Hono · FastAPI · Django · Flask · Node.js · Express · REST APIs · WebSockets · SQLAlchemy
Frontend           Next.js · React · Tailwind CSS · Zustand · Leaflet
Databases          MongoDB · PostgreSQL · Redis · ClickHouse · SQLite
Messaging          Kafka
Cloud & DevOps     AWS · Azure · GCP · Docker · Vercel · Bun
Observability      Prometheus · OpenTelemetry · Grafana Loki · Sentry
Payments           Stripe · Razorpay · OxaPay
Other              Twilio · BeautifulSoup · PIL/Pillow · Git · Linux/Unix
```

---

## Experience

### **MegaLLM** | Backend Engineer
*Remote · Nov 2025 – June 2026 · [megallm.io](https://megallm.io)*

- Sole engineer on the MegaLLM backend — a production OpenAI/Anthropic-compatible API gateway in front of 70+ LLMs on **Hono + Bun + TypeScript** with MongoDB, Redis, Kafka, and ClickHouse.
- Designed a 3-tier cache (in-memory LRU → Redis → MongoDB) hitting **>95% L0 hit rate at ~2–4 ms**, plus intelligent model routing with a MobileBERT classifier and 429/5xx fallback chains.
- Shipped **Stripe + Razorpay + OxaPay** billing with idempotent webhooks, organization wallets (free/paid/promotional credits), and ClickHouse credit-event streaming for usage correlation.
- Hardened the platform with JWT + Redis blacklist, prefix-lookup API keys, 3-tier admin RBAC, and full **Prometheus / OpenTelemetry / Grafana Loki** observability.

---

## Projects

### **Protego** | AI-Powered Personal Safety Platform
*🏆 Govt. Pre Sabka AI Hackathon — 1st Position · [Live Product](https://protego.zssh.dev)*

- Built the **FastAPI + PostgreSQL** backend with JWT (httpOnly cookies), bcrypt, SQLAlchemy ORM, SlowAPI rate limiting, and Sentry error tracking.
- Implemented a 5-second cancellable SOS countdown with parallel dispatch to SMS, WhatsApp, email, and voice via **Twilio**, plus token-based public live-tracking pages.
- Integrated multi-provider AI — **Whisper/Deepgram** for transcription, **Claude (via MegaLLM)** for distress analysis, **Azure OpenAI Realtime** for the AI Safety Call feature, and **ElevenLabs** for TTS.
- Shipped geofencing with Haversine calculations to auto-start/stop walk sessions, plus a **Next.js 15 PWA** frontend with **Leaflet** maps and **Zustand** state.

### **EduGuide** | One-Stop Career & Education Advisor
*Smart India Hackathon · [GitHub](https://github.com/Anay0305/EduGuide)*

- Developed a full-stack platform using **Node.js, Express, MongoDB, and Next.js** to improve college enrollment through personalized recommendations.
- Implemented secure authentication, role-based access control, and REST APIs for courses and recommendations.
- Integrated interactive college maps and multilingual content delivery using translation APIs.

### **Gateway** | Discord Bot & Card Graphics API
*[GitHub](https://github.com/Anay0305/Gateway-discord-bot)*

- Developed and deployed a multifunctional Discord bot with automation, moderation, and engagement features.
- Built REST APIs and a Flask-based Card Graphics API for dynamic profile cards and leaderboards.
- Scaled backend services to **635+ guilds and 1.3M+ users**, handling high-frequency events with reliable API performance and persistent storage.

---

## GitHub Analytics

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Anay0305&theme=github-dark&hide_border=true" alt="Contribution Graph"/>
</p>

<p align="center">
  <img src="https://readme-stats-gilt-alpha.vercel.app/api?username=Anay0305&show_icons=true&theme=github_dark&count_private=true&hide_border=true&cache_seconds=10" height="165"/>
  <img src="https://readme-stats-gilt-alpha.vercel.app/api/top-langs/?username=Anay0305&layout=compact&theme=github_dark&hide_border=true&cache_seconds=600&v=2&langs_count=10" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Anay0305&theme=github-dark-blue&hide_border=true"/>
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Anay0305&theme=github_dark"/>
</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Anay0305&style=flat&color=lightgray" alt="Profile Views"/>
</p>
