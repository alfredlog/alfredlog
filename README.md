<h1 align="center">Hi, I'm Alfred Mushagalusa Munganga 👋</h1>
<h3 align="center">AI Engineer · Machine Learning & Automation · Computer Science @ TU Darmstadt</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/alfred119"><img src="https://img.shields.io/badge/LinkedIn-alfred119-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/Location-Darmstadt%20%7C%20Frankfurt-2ea44f?style=flat" alt="Location">
  <img src="https://img.shields.io/badge/Open%20to-Working%20Student%20%2F%20Internship-orange?style=flat" alt="Open to work">
</p>

---

### 🧠 About me

I build **production-ready AI applications** — from ML models, RAG pipelines and AI agents to the backend, payments and servers that keep them running.

- 🎓 B.Sc. Computer Science at **TU Darmstadt** — focus on Generative AI, AI Agents & Process Automation
- 🤖 Building **LLM-powered systems**: AI agents (MCP, tool calling, human-in-the-loop), RAG, vector search
- 🏆 **2nd place, Adevar Labs prize** at the **TUM Blockchain Hackathon 2026** (TBC26 Agentic Payments, Munich, Oct 2026) with **[AgentTresor](https://github.com/alfredlog/agenttresor)** (formerly AgentGetPay)
- 📈 Built the analytics and AI assistant of **[Issuer Intelligence Hub](https://github.com/wissemsaadaoui/Futury-Build-Days-Hackathon)** at **Futury Build Days 2026** for the **Deutsche Börse challenge**
- 🧾 Building **[E-Rechnung](https://github.com/alfredlog/erechnung)** ([erechnungagent.de](https://erechnungagent.de)): an agent that checks and approves German e-invoices (XRechnung, ZUGFeRD)
- 🛠️ Strong software engineering foundation: REST APIs, multi-tenant architectures, cloud storage, auth, payments
- 📊 Background in **IT & Data Analysis** (internship at FINCA)
- 🌍 French (native) · German (C1) · English (professional)
- 🔎 Looking for **Working Student / Internship** roles in ML/AI in the Frankfurt/Darmstadt area

---

### 🚀 Featured Projects

| Project | What it does | Stack |
|---|---|---|
| **[AgentTresor](https://github.com/alfredlog/agenttresor)** (formerly AgentGetPay) · [Live](https://agentpay.pdf-libre.de) · 🥈 TUM Blockchain Hackathon 2026 | Non-custodial spend control for AI agents. The company locks a budget in an on-chain vault (Bitcoin Script): a payment needs both the agent's and the policy's signature, and the company can always take its funds back alone. Rules per agent (allowed merchants, max per payment, daily budget, in sats or euros); large payments wait until the company approves them with a signature in its own wallet. A covenant version lets every node enforce the payment cap. Hash-chained audit log anchored on-chain. Agents (Claude, ChatGPT, Cursor) connect through a local MCP service and pay merchants over HTTP 402. Live on BSV mainnet, 270+ automated tests. | TypeScript, Node.js, MCP, Bitcoin Script, BSV (BRC-100 wallets, HTTP 402), Caddy |
| **[E-Rechnung](https://github.com/alfredlog/erechnung)** · [erechnungagent.de](https://erechnungagent.de) | Receive, check, create and export German e-invoices (XRechnung, ZUGFeRD / Factur-X) for small businesses. An agent reads every incoming invoice (XML, ZUGFeRD, PDF, scan, e-mail) and approves it on its own only when it is certain: values must be found literally in the document (grounding), the arithmetic and the official KoSIT validation must pass, and a changed IBAN blocks the invoice. Everything else goes to a human with a concrete reason. Outgoing invoices as validated PDF/A-3 ZUGFeRD + XRechnung, DATEV export for the tax advisor, append-only audit log. Parses all 87 official KoSIT test invoices with 0 rule errors; 139 tests. | Python, FastAPI, HTMX, PostgreSQL, Tesseract OCR, LLM (Mistral, EU), KoSIT validator, Docker |
| **[Issuer Intelligence Hub](https://github.com/wissemsaadaoui/Futury-Build-Days-Hackathon)** · Futury Build Days 2026, **Deutsche Börse challenge** | Self-service tool for Investor Relations teams of small and mid caps: explains how their share traded on Xetra (liquidity, spread, auctions, peers) and what happened around each announcement. Anomaly detection, impact cards, editable thresholds and a decision log. An AI assistant may only rephrase computed figures: a guard rejects any number that is not in the facts. Team of four; my part: analytics and the AI assistant. | Python, pandas, FastAPI, LLM tool use, React + TypeScript |
| **[Empfang KI](https://github.com/alfredlog/empfang-ki)** · [empfang-ki.de](https://empfang-ki.de) | AI receptionist for small businesses: an embeddable chat widget answers customer questions from the business's knowledge base and takes requests and appointments via Claude tool use, forwarded by e-mail. Multi-tenant, website and PDF import, industry templates with emergency detection, customer dashboard, Stripe billing, automatic data deletion (GDPR). | Node.js, Express, Claude API, PostgreSQL, Stripe, Docker |
| **[PDF Libre](https://github.com/alfredlog/pdf-tools)** · [pdf-libre.de](https://pdf-libre.de) | Public web app with free PDF tools (merge, compress, convert, edit), Pro plan and day pass, and a pay-per-call API for AI agents. Built and run on my own Linux server. | Node.js, PostgreSQL, Stripe, Linux VPS (pm2, Caddy) |
| **[AI Customer Support Platform (chatboot)](https://github.com/alfredlog/chatboot)**  | Multi-tenant SaaS for AI support chatbots: companies upload documents, the bot answers via RAG with semantic search. Auth, customer management, billing. | Node.js, Express, OpenAI, PostgreSQL + pgvector, AWS S3, Stripe |
| **[AI Use-Case Prioritization Copilot](https://github.com/alfredlog/AI-Use-Case-Prioritization-Copilot)** | ML model that scores and prioritizes AI use cases, plus a RAG-based insights copilot that explains the recommendations. | Python, scikit-learn, LLM APIs, RAG |
| **Computer-Vision Safety Monitoring** | Real-time object detection for safety monitoring on video streams. | Python, YOLOv8 |
| **Invoice Recognition Agent** | AI agent that scans a mailbox (IMAP), recognizes invoices, extracts fields with an LLM and files them with a log. | Python, IMAP, Claude API |

---

### 🧰 Tech Stack

**AI / ML**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI%20API-412991?style=flat&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic%20API-191919?style=flat&logo=anthropic&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-00FFFF?style=flat)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat)
![RAG](https://img.shields.io/badge/RAG%20%26%20Agents-6E40C9?style=flat)
![MCP](https://img.shields.io/badge/MCP-Model%20Context%20Protocol-111111?style=flat)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![OCR](https://img.shields.io/badge/Tesseract%20OCR-5A5A5A?style=flat)

**Backend & Data**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL%20%2B%20pgvector-4169E1?style=flat&logo=postgresql&logoColor=white)
![REST](https://img.shields.io/badge/REST%20APIs-FF6C37?style=flat)

**Cloud & Tools**
![AWS S3](https://img.shields.io/badge/AWS%20S3-569A31?style=flat&logo=amazons3&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat&logo=stripe&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux%20Server-FCC624?style=flat&logo=linux&logoColor=black)
![Blockchain](https://img.shields.io/badge/BSV%20Blockchain-EAB300?style=flat)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**ML Foundations (TU Darmstadt – Statistical Machine Learning)**
Regression & classification · SVMs & kernel methods · Neural networks & CNNs · Ensemble methods (Random Forest, Boosting) · Clustering, GMMs & EM · PCA · Convex optimization

---

### 📈 GitHub Stats

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=alfredlog&show_icons=true&hide_border=true&theme=default" alt="GitHub stats">
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=alfredlog&layout=compact&hide_border=true" alt="Top languages">
</p>

---

<p align="center"><i>"I turn LLMs into reliable products — not just demos."</i></p>
