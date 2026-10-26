<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/xmglord/xmglord/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/xmglord/xmglord/output/github-snake.svg" />
    <img alt="Contribution graph eaten by a snake" src="https://raw.githubusercontent.com/xmglord/xmglord/output/github-snake.svg" />
  </picture>
</div>

## Hi, I'm German 👋

**AI Application Engineer · LLM agents for business systems.**

I build software where business systems meet LLMs. My foundation is ERP: years of Odoo development and migrations, from custom modules and third-party integrations to the infrastructure they run on. That's the part most AI projects underestimate: the data model, the workflows, and what breaks in production. Now I build with LLM agents every day, spec-first and with the model kept on a short leash: it interprets messy input, code does the math and enforces the rules.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Odoo](https://img.shields.io/badge/Odoo-714B67?style=flat&logo=odoo&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat&logo=claude&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

### 🧭 What I do
- Implement and migrate **Odoo** end to end: custom modules, integrations, fiscal localizations, data migrations.
- Run the infrastructure around it on **AWS**, with CI on **GitHub Actions** and pre-commit standards.
- Automate the systems that stay: browser automation where APIs fail, bots that turn chat workflows into structured ERP data.
- Build with **LLM agents** daily: subagents, persistent project memory, one setup versioned across machines.

### 📈 A few things I have shipped
- **20+ end-to-end Odoo migrations** (v15–v17) across every core module, plus integrations (Mercado Libre APIs) and fiscal localizations for Mexico, Peru and the US.
- Migrated a **100GB production database** by working around a framework-level batch-update limitation that blocked the standard path.
- An **AWS browser-automation service** (Playwright) that restored bulk CFDI downloads after SAT API changes broke the standard integration.
- A **Telegram bot** that replaced a WhatsApp payment workflow with structured approvals in Odoo that trigger invoicing automatically.
- Found and fixed a calculation bug in a proprietary commissions module during its migration; the fix went upstream.

### 🔧 Featured work
- **[Auditing users and permissions in a legacy ERP](case_studies/aspel_user_audit.md)**: reverse-engineered an undocumented Firebird schema and built a report → review → guarded cleanup cycle for Aspel SAE/BANCO, with a single atomic write path, rehearsal and verified backups.

- **[AltScore Makers Challenge](case_studies/altscore_makers_challenge.md)**: 8 of 9 hiring puzzles against a live API in about a day, enough for the CTO interview; I planned each solution and Claude Code wrote the code from that plan.

- **[Engineering standards for a holding's Odoo rollout](case_studies/odoo_engineering_standards.md)**: Odoo.sh as the runbot, fast-forward releases, GitHub rulesets designed around the platform's real limits, and a lint gate proven with negative tests, all in place before the first custom module.

- **[firefox-mcp-launcher](https://github.com/xmglord/firefox-mcp-launcher)**: runs Mozilla's Firefox DevTools MCP against a dedicated Firefox instance, alongside the everyday browser. The instance runs Marionette and BiDi and uses a clean profile by default, so the agent never inherits logged-in sessions. Also documents the failure modes I hit, such as a second MCP client locked out of Marionette behind an opaque error, and the launch command that silently starts nothing (fixed upstream in my merged docs PR [mozilla/firefox-devtools-mcp#220](https://github.com/mozilla/firefox-devtools-mcp/pull/220)).

<!-- TODO more featured work as it lands: hosting migration case study, health_planner. -->

### 🛠 Daily tools
**ERP** Odoo (v15–v19), QWeb, OWL<br>
**Languages** Python, JavaScript, SQL, Bash<br>
**Data** PostgreSQL<br>
**Cloud & delivery** AWS (EC2, IAM), Docker, GitHub Actions, pre-commit<br>
**Automation** Playwright, Telegram Bot API<br>
**AI** Claude Code, LLM agents

### 📫 Let's talk
- **LinkedIn:** [German Loredo Becerra](https://www.linkedin.com/in/german-loredo-becerra-2a52a2235/)
