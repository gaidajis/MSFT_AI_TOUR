# Microsoft AI Tour Zürich 2026

> Personal findings, architecture notes, and strategic summaries from the Microsoft AI Tour — Zürich, April 2026.

## 🌐 Interactive Website

A fully interactive, searchable executive hub is available at:

👉 **[https://gaidajis.github.io/MSFT_AI_TOUR/](https://gaidajis.github.io/MSFT_AI_TOUR/)**

The site is built as a single-page static application deployed automatically to GitHub Pages on every push to `main`.

### Site Features

- **🔍 Live search** — instantly filter content across all sections
- **9 navigation tabs** — structured by topic and audience
- **Mermaid.js architecture diagrams** — visual flows for IQ Stack, Agent Factory, Zero Trust, and Higher Education
- **Code examples** — MCP server snippets, Graph API permission schemas
- **Role-based persona filtering** — content tailored to each stakeholder type
- **4-phase implementation roadmap** — from Foundation to Frontier Firm status
- **Responsive design** — works on desktop, tablet, and mobile

### Navigation Tabs

| Tab | Contents |
|---|---|
| 📊 **Overview** | Key themes, Agent Factory, ROI model, platform architecture diagram, quick stats |
| 🧠 **IQ Stack** | Work IQ, Fabric IQ, Foundry IQ — with sequence diagram, MCP, Graph API code examples |
| 🤖 **Agents** | Agent Factory, Agent 365 control plane, Copilot Studio, Ownerless Agents, Agentic DevOps |
| 🔒 **Security** | Zero Trust model, Confidentiality Inheritance, Entra Policies, Purview Dashboard, Agentic Defense |
| 💰 **Finance** | LGT, Migros Bank, Vaudois Assurances — Swiss financial services case studies + FINMA considerations |
| 🎓 **Education** | Higher education architecture (e.g. EHL), student journey agents, SIS integration, GDPR/nFADP |
| 👥 **By Role** | Guidance for Director of IT, Cyber Security, AI Architect, IT PM, Cloud, Data Owners |
| 🗺️ **Roadmap** | 4-phase implementation plan: Foundation → Build → Scale → Frontier Firm |
| 📋 **Sessions** | Full index of all 5 attended sessions with codes and key takeaways |

---

## 📄 Markdown Summary

For a detailed, persona-based executive summary including the Microsoft IQ Stack, Agent Factory, and Security deep-dives:

👉 **[MS AI Tour Zürich 2026 — Executive Summary](./MS_AI_TOUR_ZURICH_2026.md)**

---

## 📋 Sessions Covered

| Code | Title | Key Theme |
|---|---|---|
| `LTG122-CH` | Copilot Control System | Governance, ROI measurement, Purview |
| `BRK202-CH` | Financial Services AI | LGT, Migros Bank, Vaudois — Swiss case studies |
| `BRK320-CH` | Becoming a Frontier Firm | IQ Stack, Agent 365, Agent Factory at scale |
| `BRK340-CH` | Driving Business Innovation | Agentic DevOps, Cowork patterns, Foundry |
| `BRK380-CH` | End-to-End Security | Zero Trust, Agentic Defense, Sentinel, Purview |

---

## 🏗️ Topics Covered

- **The Intelligence Stack** — Work IQ (Teams/Outlook), Fabric IQ (OneLake/Power BI), Foundry IQ (RAG/SharePoint)
- **Agent Governance** — Agent Factory operating model, Agent 365 control plane, Ownerless Agents
- **Security & Compliance** — Purview sensitivity inheritance, Entra behavioral policies, Agentic Defense
- **Industry Insights** — LGT, Migros Bank, Vaudois Assurances transformation journeys
- **Higher Education** — Applying the Microsoft AI platform to academic institutions and student journeys
- **Future Tech** — Majorana 1 Quantum Processor, 3D Visualization with Nvidia + Fabric
- **MCP (Model Context Protocol)** — Standardized agent connectors for Dynamics 365, Workday, Oracle, SAP

---

## 👥 Target Audiences

| Role | Focus |
|---|---|
| **Director of IT** | Strategy, ROI measurement, Agent Factory adoption |
| **Cyber Security Director** | Zero Trust, Purview labels, Entra Policies, Agentic Defense |
| **AI Architect** | IQ Stack design, MCP connectors, Foundry/Fabric/Work layers |
| **IT Project Managers** | Implementation roadmap, phased rollout, governance setup |
| **Cloud & Infrastructure** | Sovereign Cloud, OneLake, hybrid deployment, Fabric IQ |
| **Data Owners** | Purview data governance, sensitivity labels, GDPR/nFADP compliance |

---

## 🚀 Deployment

The site is auto-deployed to GitHub Pages via a static deployment workflow:

```yaml
# .github/workflows/jekyll.yml
# Deploys pre-built static files from ./docs to GitHub Pages on push to main
```

No build step required — HTML is pre-built. Any push to `main` triggers a live update.

---

## 📜 License

This work is licensed under a [Creative Commons Attribution 4.0 International License](./LICENSE).

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

You are free to share and adapt this material for any purpose, provided appropriate credit is given.

---

*Findings based on Microsoft AI Tour Zürich — April 2026. Content reflects personal notes and interpretation; not an official Microsoft publication.*
