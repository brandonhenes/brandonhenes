# Brandon Henes

AI & Automation Builder (n8n • LLMs • APIs) | Operations → Solutions / Implementation  
Minneapolis–St. Paul (remote/hybrid OK)

I run a Tier-5 Walgreens store doing ~$20M revenue and ~$3M EBITDA with ≤0.11% labor variance on ~900 hrs/week, OT ≤2.2%, queues down ~300/day, DOH −39%/−67%, and record-low shrink.  
Now I build AI + workflow automations so ops, pharmacy, and RevOps teams can get the same control without adding headcount.

---

## Summary
- Design and ship n8n workflows that call LLMs, external APIs, and business apps.
- Add the “unsexy” parts most people skip: logging, error lanes, ownership, and run history.
- Translate operational problems (labor, intake, queue, inventory) into automations business leaders can audit.

---

## Core Skills
**Automation & Integrations**
- n8n, webhooks, REST APIs, OAuth2
- Google Sheets API, Gmail, form/webhook triggers
- Claude Desktop via MCP
- Error handling, retries, notifications

**AI / Agent Patterns**
- LLM classify, extract, route, generate
- Basic RAG / tool calling
- Structured output → Sheets / CRM

**Business Systems / RevOps**
- Intake → enrichment → routing
- CRM/helpdesk style flows
- Reporting hooks for ops

**Data / Reporting (supporting)**
- SQL (Postgres/MySQL)
- Python (pandas)
- Excel (advanced), Power BI / Tableau

---

## Selected Automations

### 1. Email-to-Structured-Record with LLM and Error Lane
**Goal:** turn unstructured ops email into a trackable queue.  
**Flow:** inbound email → n8n → Claude (classify: billing/support/Rx/other) → write structured row to Google Sheets → optional reply → on failure, send alert.  
**Value:** same discipline I used to control queues and labor, but automated.

### 2. Daily Ops KPI Agent
**Goal:** give ops leaders the story, not just the numbers.  
**Flow:** schedule → pull KPIs → LLM summary → email to stakeholders.  
**Value:** execs don’t have to open a dashboard.

### 3. CRM / Lead Enrichment and LLM Routing
**Goal:** support GTM/RevOps teams.  
**Flow:** new lead → enrichment/API → LLM decides owner/segment → update system → notify channel.  
**Value:** shows I can work outside retail/healthcare and into SaaS/revops.

(Include links to: short demo video, workflow JSON, screenshot of run log.)

---

## Operations Background (Why I’m credible in front of business)
- ~$20M Walgreens store, ~\$3M EBITDA
- Labor: ≤0.11% variance on ~900 hrs/week
- OT: ≤2.2%
- Queue reduction: ~300/day
- DOH: −39% / −67%
- Record-low shrink

I now build automations that protect these numbers by making every run loggable and every failure visible.

---

## Current Focus
- Customizing n8n (Node.js basics)
- Salesforce / HubSpot admin-level automations
- LLM evaluation and monitoring
- Packaging workflows as repeatable demos for mid-size consultancies

---

## How to Evaluate Me
1. Give me an intake email and ask for a structured row + reply.
2. Ask me to call an API and only alert on non-200.
3. Ask me to add an LLM classification step to an existing no-code flow.
4. Ask me to show the run history.

---

## Contact
brandonhenes@gmail.com  
Target roles: Solutions Engineer (Automation/AI), Automation/Workflow Engineer, Implementation Consultant (iPaaS/AI), Business Systems/Integrations, RevOps Automation, AI Automation Engineer
com
