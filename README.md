![Ali Nauman — Senior Full Stack Engineer working with Angular, TypeScript and Node.js](assets/profile-header.svg)

<p align="center">
  <strong>Utrecht, Netherlands 🇳🇱 · 8+ years building software</strong><br />
  <a href="https://www.linkedin.com/in/alinauman1/">LinkedIn</a> ·
  <a href="mailto:ali60351@gmail.com">Email</a> ·
  <a href="https://github.com/Ali60351?tab=repositories">Repositories</a>
</p>

I build B2B products with complex interfaces and the APIs behind them. At **Fashion Cloud**, I deliver **ordering and replenishment** end to end using Angular, TypeScript and Node.js, with MongoDB and Elasticsearch. The platform serves around 250 brands and 14,000 retailers.

I'm interested in **senior full stack and frontend engineering opportunities in the Netherlands**, especially teams where I can own work from product requirements through production.

I'm a Dutch highly skilled migrant (HSM) residence permit holder, and a new employer must be an IND-recognised sponsor.

## 🧩 Selected work

- **Multi-store auto-restock:** Delivered the Angular interface and Node.js APIs, from feature flag to general availability, so 190 brands manage the stores of about 8,000 retailers from one screen. Led the scheduling change: explicit active, paused and inactive states replaced a date-field workaround about 100 brands relied on.
- **Performance:** Cut p75 load time of the reorder product page in production (Datadog RUM) by more than half, from 3.6 s to 1.6 s, by fixing a per-article retailer-group lookup in the product API: it now runs once per request, with catalog access checks running concurrently.
- **Project technical lead:** Development captain on add-article, initial delivery and schedule replenishment, accountable for delivery. Wrote acceptance criteria for the strategy list, split epics into frontend and backend tickets for three engineers, and owned the API contract. Ran knowledge-sharing sessions on Elasticsearch and Angular change detection.
- **Production reliability:** Traced orders stuck before export to the order engine missing its SQS messages, then built an hourly AWS EventBridge and Terraform monitor that alerts the team in Slack. It caught 25 stuck orders from July to October 2026, all recovered, and prompted a project to retry failed orders automatically.
- **Shared size matrix:** Centralized size logic (waist and length, letter and plus sizes, prepacks) into one service shared by ordering and replenishment, replacing duplicated grid logic, and carried size data into Elasticsearch filters.
- **Brand page builder:** Co-built a multilingual builder, contributing drag-and-drop editing, asset uploads, previews and supporting APIs.
- **Security:** Moved authenticated image loading from query-string tokens to Authorization headers with client-side blob caching and backwards-compatible server support.

## 🛠️ Tools I work with

| Area | Technologies |
| --- | --- |
| Frontend | Angular, TypeScript, RxJS, React, Redux, JavaScript |
| Backend & data | Node.js, REST APIs, MongoDB, PostgreSQL, Elasticsearch |
| Infrastructure, testing & observability | AWS (EventBridge, SQS, S3), Docker, Terraform, Datadog, Jest |
| Earlier work (Arbisoft) | Python, Django, Django REST Framework |

## 🤖 How I work

I settle the contract before writing code. When a feature starts, I check the ticket against its PRD, Figma designs and API, and resolve each gap with a decision, not an assumption. Then I split the work into frontend and backend tickets and hold the code to a written standard (the B2B style guide I authored, enforced with ESLint). I work in Cursor with a spec, plan and subagent-implementation workflow, with a reviewer per task, built on open-source skills such as Superpowers. I wrote custom skills that run the first check and recommend how to settle each gap. I make the call.

## Previously at Arbisoft

From **2018 to 2022**, I worked on recruitment, e-commerce and internal operations products. I built most of the React frontend for **Hirestream**, an in-house applicant-tracking system, including authentication, rich-text editing, OAuth integrations, real-time updates over WebSockets and Stripe payments. I also worked on **Unstack's** Shopify landing-page platform and **Workstream's** internal ERP.

## 🌱 From the workshop

**[Material RTE](https://github.com/Ali60351/material-rte)** — A React/TypeScript rich-text editor built on Draft.js and styled with Material UI, with custom themes, variables and hyperlinks. [View the npm package →](https://www.npmjs.com/package/material-rte)

<details>
<summary>A few earlier projects</summary>

- **[Seiyuu Nostalgia](https://github.com/Ali60351/seiyuu-nostalgia)** — Explore voice-actor connections across anime you've watched. Vue and GraphQL.
- **[Image Processing API](https://github.com/Ali60351/image-processing-api)** — Image resizing and conversion with Sharp, Express and TypeScript.
- **[Quick-FIV](https://github.com/Ali60351/Quick-FIV)** — A desktop file-integrity checker built with Node.js, Electron and Vue.
- **[Warframe Alerts](https://github.com/WFCD/warframe-alerts-win)** — Earlier desktop work with C# and Windows Forms.

</details>

---

**Education:** B.S. in Computer Science, FAST National University (2014–2018)  
**Languages:** English (professional working proficiency), Dutch (learning)
