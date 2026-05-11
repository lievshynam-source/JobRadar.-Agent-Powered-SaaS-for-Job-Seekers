# JobRadar — Agent-Powered SaaS for Job Seekers

JobRadar is an agent-powered SaaS prototype that monitors selected company career pages and notifies users when relevant roles appear.

It explores agent UX, explainability, and decision-support workflows for a job search experience that helps users avoid noise, save time, protect privacy, and apply earlier.

## Open Prototype

[Launch Interactive Dashboard Prototype](https://lievshynam-source.github.io/JobRadar.-Agent-Powered-SaaS-for-Job-Seekers/jobradar-dashboard.html)

> Standalone HTML prototype. No backend, no API, no setup required.
---

## Human–AI Triad Collaboration

| Role | Contribution |
|---|---|
| **Maryna Lievshyna** | Founder, Product Design Lead, product vision, final decisions |
| **ChatGPT** | PM, UX structure, case study support |
| **Claude + Cursor** | UI execution, front-end engineering, interactive prototype |

This project was built through an experimental Human–AI triad workflow: close enough to a real product team, but without Zoom calls, endless emails, and meetings that could have been a sentence.

The setup included brainstorming, challenging assumptions, resolving disagreements, separating responsibilities, and calibrating each AI tool until it passed the team-fit test. Each “team member” had a role, a voice, and a clear layer of responsibility.

I led the vision, made the final calls, and used AI tools as product, design, and engineering support.

---

## Problem

Job searching in 2026 is brutal.

You open LinkedIn “just to check jobs,” and suddenly you are buried under irrelevant listings, endless alerts, recruiter spam, and success posts from people who apparently built a €50M AI startup before breakfast.

Meanwhile, you are just trying to find a good role, apply early, and not emotionally crash after scrolling through hundreds of applications.

For employed professionals, there is another layer: they may be open to new opportunities, but they do not want to risk public “Open to Work” visibility.

And yes, tools like Apify, Claude workflows, scraping scripts, cloud setups, and notification systems - proper life savers, but require some basic tech skills. I want to give the same experience for non-technical users.

---

JobRadar is a simple private job tracking tool for people who want to apply for a job. Simple.

Instead of searching the whole internet, users choose the companies they want to work in. The agent monitors those career pages, finds relevant roles, explains why they match, and helps users decide what to save, ignore, or apply to.

The idea is simple:

> Pick your dream companies. Set your preferences. Let the agent watch the boring part.

## Dashboard Preview

## Dashboard Preview

![JobRadar dashboard preview](./jobradar-dashboard%20Strong%20maches.png)

The dashboard is designed to answer three questions fast:

- what happened
- what matters now
- what should I do next

## Who It Is For

---

## Who It Is For

JobRadar is for:

- active job seekers tired of LinkedIn noise
- people who want to apply early to companies they choose
- employed professionals who are open to opportunities but want privacy
- non-technical users who do not want to configure automation tools
- AI tech people too, if they want the easy button

---

## Simple Flow

1. Pick your dream-job companies
2. Set your preferences
3. Let the agent monitor them
4. Review only relevant roles
5. Save, ignore, or apply faster

**Free to use for job seekers.**


## What Is Included

This case study includes three prototype layers:

1. **Product flows**
   - Pre-onboarding flow
   - Onboarding flow
   - Main app flow
   - Agent Activity / Trust flow
   - Dashboard flow

2. **Interactive prototypes**
   - Onboarding prototype
   - Dashboard prototype
   - Matches page
   - Job Detail page
   - Agent Activity page

3. **Local agent simulation**
   - Reads local JSON data
   - Simulates company monitoring
   - Scores jobs with deterministic logic
   - Generates match explanations
   - Updates dashboard states
   - Simulates source issues
   - Supports save / ignore actions

   ## Prototype Layers

JobRadar was developed in layers, from product logic to coded prototype.

### 1. Product Flows

The first layer defines how the product works before focusing on UI polish.

Mapped flows include:

- Pre-onboarding: helps users understand the product promise before setup
- Onboarding: collects companies, preferences, alerts, and review confirmation
- Main App Flow: defines the core SaaS navigation and user actions
- Agent Activity / Trust Flow: shows what the agent checked, found, filtered, or failed to access
- Dashboard Flow: turns agent results into clear states and next actions

### 2. Onboarding Prototype

The onboarding prototype explores how users configure the agent.

Instead of treating onboarding as a generic form, the setup flow is designed as a way for the user to teach the agent what to watch for:

- target companies
- preferred roles
- locations
- seniority
- keywords
- alert preferences
- review before first scan

### 3. Dashboard Prototype

The dashboard prototype shows the core SaaS experience after setup.

It is designed to answer three questions quickly:

1. What happened?
2. What matters now?
3. What should I do next?

The dashboard includes:

- AI summary
- top matches
- saved jobs / pipeline
- tracked companies
- agent activity
- source status
- dashboard states

### 4. Local Agent Simulator

The local agent simulator is not a real AI agent yet.

It is a lightweight front-end simulation that makes the product logic testable before building a real backend.

It simulates:

- company source checks
- job scoring
- match explanations
- filtered jobs
- source errors
- activity logs
- dashboard state updates
- save / ignore feedback


## What Is Real vs. Simulated

### Real

- Product concept
- UX flows
- Information architecture
- SaaS dashboard structure
- Onboarding logic
- Trust and explainability patterns
- Interactive HTML prototype
- Local JSON data structure
- Deterministic scoring logic
- Dashboard states
- Save / ignore interactions

### Simulated

- Real career-page scraping
- Real AI / LLM reasoning
- Backend infrastructure
- User accounts
- Persistent database
- Live notifications
- Live job availability

This prototype is designed to prove the product experience, not production readiness.
