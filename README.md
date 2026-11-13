# Hi, I'm Johnmark Enriquez 👋

### Senior Full-Stack Software Engineer | Laravel · React · TypeScript · AI-Assisted Development

I'm a senior full-stack engineer with **6+ years of experience** building healthcare platforms, business systems, mobile apps, and APIs. At WEND Philippines, I work with my team on healthcare products, including the Firewatch Health React Native app and the DentalRay dashboards.

My core stack is **Laravel/PHP, React, TypeScript, React Native, and PostgreSQL/MySQL**. I use AI coding agents (Claude Code, OpenAI Codex) every day, guided by written project rules and custom skills. I verify every change with tests (Vitest, Pest, Playwright), CI checks, and my own review of the code and logic, and I mentor teammates to work the same way.

🌐 **Portfolio:** [johnmark.tech](https://www.johnmark.tech/)  
💼 **LinkedIn:** [johnmark-enriquez](https://www.linkedin.com/in/johnmark-enriquez)

---

## 🛠️ Tech Stack

**AI-Assisted Development**
- Claude Code, OpenAI Codex, multi-agent workflows, custom skills, MCP servers
- Project rules (CLAUDE.md, AGENTS.md)
- Claude API integrations with human-in-the-loop approval and cost logging

**Backend & APIs**
- PHP, Laravel, Rust (axum)
- REST API design, authentication, third-party integrations

**Frontend & Mobile**
- React, Next.js, TypeScript, JavaScript
- Tailwind CSS, shadcn/ui
- React Native, Expo, NativeWind

**Databases**
- PostgreSQL, MySQL/MariaDB, Supabase
- Relational data modeling, migrations, and query optimization

**Testing & Quality**
- PHPUnit, Pest, Vitest, Playwright, pytest, pgTAP, MSW
- Test-first development, code review, CI checks

**Cloud & Infrastructure**
- Docker, Git, Linux, Nginx
- DigitalOcean, Linode, Vercel, AWS S3
- Production deployment and troubleshooting

**Currently exploring:** Node.js, Express.js, Go

---

## 🚀 Featured Work

### Nudgewright — Human-Approved Automation Engine (Rust)

An open-source Rust engine for reminder automation in which a person approves exactly what gets sent. Each approval is tied to a content hash, every message is sent exactly once (even across crashes), and every action is recorded in an append-only audit log. The AI only words the drafts, and its token cost is logged per call.

**Built with:** Rust, PostgreSQL, Claude API, with written agent rules, about 127 tests, and CI on every push.

→ [github.com/Enriquez-Johnmark/nudgewright](https://github.com/Enriquez-Johnmark/nudgewright)

### Kompleto and Balanse — Products Built on Nudgewright

- **Kompleto** automates document and BIR-deadline follow-ups for Philippine bookkeepers.
- **Balanse** sends polite payment follow-ups for small businesses and stops as soon as the client replies or pays.

Both keep human approval built in.

**Built with:** Rust, axum, Claude API, React.

### Healthcare AI with Human Approval (FHIR R4)

Four projects in which the AI drafts or explains and a person makes the decision. Each one is backed by acceptance criteria that are proven by tests.

- **Record Access Audit:** flags unusual access to patient records for a clinic's privacy officer and explains each case. *Python, FastAPI, PostgreSQL, React.*
- **Care Message Assistant:** drafts replies to patient portal messages for clinicians to approve. *TypeScript, Fastify, PostgreSQL, React.*
- **Care Reminders:** emails follow-up reminders to patients who are due, with coordinator approval and sending limits. *Rust, axum, PostgreSQL, React.*
- **Lab Report Assistant:** writes plain-language lab reports that a physician approves. *Rust, axum, PostgreSQL, React.*

### More AI and Automation

- **Review Triage Agent:** sorts app reviews by cause and drafts replies for approval. *TypeScript, Claude API, MCP, n8n, SQLite, React.*
- **Help Assistant:** answers customer questions in Taglish, Tagalog, or English from help pages, with 88% correct answers on 150 test questions. *Python, Claude API, FastAPI, BM25.*

### Aegir — Fleet Operations & Safety

A multi-tenant maritime safety and fleet operations workspace covering vessels, inspections, work orders, and shift handovers, with a full audit trail.

**Built with:** Next.js, TypeScript, Supabase, PostgreSQL, Vitest, Playwright.

### Healthcare Platforms (WEND Philippines, with the team)

- **Firewatch Health:** a health platform for firefighters, with a web platform and a React Native app that includes AI features.
- **DentalRay:** separate dashboards for dental clinics, radiologists, and admin staff.

### Client Work

- **Quality Daily (QOBAL Media GmbH):** iOS and Android apps plus a companion web app on one shared Supabase backend. *React Native, Expo, React, TypeScript.*
- **JOMIS (Bread By Patty Corp.):** a bakeshop management system covering production, sales, and cash workflows. *PHP, CodeIgniter, Laravel, MariaDB.*

---

## 💡 Engineering Principles

- **Verify, don't trust:** AI output ships only after the tests pass and I have reviewed the code and logic myself.
- **Maintainability:** I write clear code on an architecture that others can understand.
- **Reliability:** I test the important business rules and handle failures deliberately.
- **Data integrity:** I design systems that keep information correct and consistent.
- **Practical engineering:** I choose solutions that fit the real requirements and avoid unnecessary complexity.

---

## 🤝 Let's Connect

I'm open to senior full-stack and AI-first engineering roles.

🌐 Visit my [portfolio](https://www.johnmark.tech/) or reach me on [LinkedIn](https://www.linkedin.com/in/johnmark-enriquez).
