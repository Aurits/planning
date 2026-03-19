---
title: "AIBOS Uganda: Must-Do Action Plan"
header-includes: |
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=JetBrains+Mono:wght@400;500&display=swap');
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
    html { background-color: #ffffff; }
    body {
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
      font-size: 10.5pt; line-height: 1.75; color: #1a1f36;
      width: 100%; max-width: none; margin: 0; padding: 20px 0 36px;
    }
    h1 {
      font-size: 20pt; font-weight: 700; color: #1a1f36;
      border-bottom: 3px solid #3b5bdb; padding-bottom: 10px;
      margin-top: 40px; margin-bottom: 18px;
      page-break-before: avoid; page-break-after: avoid;
    }
    h2 {
      font-size: 14pt; font-weight: 600; color: #3b5bdb;
      border-left: 4px solid #3b5bdb; padding-left: 12px;
      margin-top: 0; margin-bottom: 16px;
      page-break-before: always; page-break-after: avoid;
    }
    h3 {
      font-size: 11.5pt; font-weight: 600; color: #1a1f36;
      border-bottom: 1px solid #c8cfe8; padding-bottom: 5px;
      margin-top: 26px; margin-bottom: 10px;
      page-break-after: avoid; orphans: 3; widows: 3;
    }
    h4 {
      font-size: 9.5pt; font-weight: 700; color: #3b5bdb;
      text-transform: uppercase; letter-spacing: 0.07em;
      margin-top: 20px; margin-bottom: 8px;
      page-break-after: avoid;
    }
    p { margin-bottom: 12px; orphans: 3; widows: 3; }
    ul, ol { margin: 8px 0 14px 24px; }
    li { margin-bottom: 5px; }
    blockquote {
      background: #f0f4ff;
      border-left: 4px solid #3b5bdb;
      border-top: 1px solid #c5cbf9;
      border-right: 1px solid #c5cbf9;
      border-bottom: 1px solid #c5cbf9;
      padding: 12px 18px;
      margin: 18px 0; font-style: italic; color: #1a1f36;
    }
    blockquote p { margin: 0; }
    pre {
      background: #1e2030; color: #c0caf5;
      padding: 16px 20px; margin: 16px 0;
      font-family: 'JetBrains Mono', 'Fira Code', 'Courier New', monospace;
      font-size: 8.5pt; line-height: 1.6; page-break-inside: avoid;
      border: 1px solid #2d3561;
    }
    code {
      font-family: 'JetBrains Mono', 'Courier New', monospace;
      font-size: 8.5pt; background: #eef0fb; color: #364fc7;
      padding: 2px 6px; border: 1px solid #c5cbf9;
    }
    pre code { background: transparent; color: #c0caf5; padding: 0; border: none; }
    table {
      width: 100%; border-collapse: collapse; margin: 18px 0;
      font-size: 9.5pt; page-break-inside: avoid;
      border: 1px solid #c8cfe8;
    }
    thead tr { background: #1a1f36; color: #ffffff; }
    thead th {
      padding: 10px 14px; text-align: left;
      font-weight: 600; font-size: 9pt; letter-spacing: 0.04em;
      border-right: 1px solid #2d3561;
    }
    thead th:last-child { border-right: none; }
    tbody tr { border-bottom: 1px solid #c8cfe8; }
    tbody tr:nth-child(even) { background: #f5f7fc; }
    tbody tr:last-child { border-bottom: none; }
    td { padding: 9px 14px; vertical-align: top; border-right: 1px solid #e2e6f0; }
    td:last-child { border-right: none; }
    hr { border: none; border-top: 1px solid #c8cfe8; margin: 36px 0; }
    strong { font-weight: 600; }
    a { color: #3b5bdb; text-decoration: none; }
    header#title-block-header { display: none; }
  </style>
---

# AIBOS Uganda: Must-Do Action Plan

### The 11 actions required for the Delivery Framework to function

**Version 3.0 — March 2026**

> **How to use this document:** This is the action-focused companion to the full System-Driven Delivery Framework. It contains only the items that must be completed for the framework to work. Each item explains what it is, why it matters, what you need to do, who owns it, and when it must be done. For deeper context on any item, refer to the section number noted in the full framework document.

---

| # | Action | Category | Owner | Deadline |
| - | ------ | -------- | ----- | -------- |
| 1 | PMO & PdMO Integration Mapping | Governance | Management Owner | March 2026 |
| 2 | Async PR Review — AI Code Review Tool | QA | Product Manager + Management Owner | March 2026 |
| 3 | QA Owner Nomination | QA | Each team PM | March 2026 |
| 4 | Google Drive Folder Structure | Operations | Product team | March 2026 |
| 5 | Shadow / Backup Assignments | Operations | Management Owner + PMs | March 2026 |
| 6 | KPI Dashboard Activation | Operations | Management Owner | March 2026 |
| 7 | Designated Weekly Communicator (DWC) | Communication | Each team PM | March 2026 |
| 8 | Split EOD Report — Client vs. Internal | Reporting | Each team PM | March 2026 |
| 9 | E2E Testing Framework — Playwright | QA | Development team | April–May 2026 |
| 10 | AI Code Review Tool — Selection & Trial | Technology | Product Manager | March 2026 |
| 11 | No Ticket, No Code — Enforcement | Governance | All PMs + Product Manager | March 2026 — ongoing |

---

## 1. PMO & PdMO Integration Mapping

**What it is:** AIBOS Uganda operates under three governance layers — C-2 PdMO, C-3 PMO, and the System Framework. Without clear ownership boundaries, the same responsibility can end up owned by two layers at once, creating confusion and wasted effort.

**Why it matters:** If the team does not know which layer owns a decision, they either escalate everything (slowing things down) or escalate nothing (letting problems grow). Clear ownership means the right person acts at the right time.

**What to do:**

- Review the responsibility table in Section 17.3 of the main framework
- Confirm that all PMs and the Management Owner understand which tool is the master record for tasks (GitHub Projects — C-3 PMO) versus quality metrics (Google Sheets KPI Dashboard — System Framework)
- Confirm that the EOD Report and Internal SitRep are understood as two separate documents (see Item 8)
- Raise any unresolved ownership questions at the first Tuesday PDMO meeting

**Owner:** Management Owner (Ambrose)
**Deadline:** March 2026 — confirm at first PDMO meeting

> **Full reference:** Section 17 of the System Framework

---

## 2. Async PR Review — Transition from Peer Review Meeting

**What it is:** Layer 1 of the QA system is a code review that happens on every Pull Request before it is merged. The previous approach was a daily meeting where the team reviewed code together. This is being replaced with an asynchronous model — an AI tool reviews every routine PR automatically, and the Product Manager reviews major PRs manually.

**Why it matters:** A daily code review meeting is expensive in team time and tends to become a formality over time. An async AI review is available on every PR, is consistent, and costs a fraction of the team's time.

**What to do:**

- Select and subscribe to an AI code review tool (candidates: CodeRabbit, GitHub Copilot code review, Graphite) — trial one tool for one sprint before committing
- Configure the tool to run automatically on every Pull Request in all project repositories
- Confirm that the Product Manager will manually review any PR that meets the "major PR" criteria (see Item 10 / Section 6.2a of the main framework)
- The 16:30 slot is no longer a code review meeting — it is the async QA Owner staging check only (see Item 3)

**Owner:** Product Manager + Management Owner
**Deadline:** March 2026

> **Full reference:** Sections 6.2, 6.2a, 6.8 of the System Framework

---

## 3. QA Owner Nomination

**What it is:** Every project needs a named QA Owner — the person responsible for running the smoke test checklist on every staging deployment, signing off the Definition of Done, and logging pre-delivery bugs in the KPI sheet.

**Why it matters:** Without a named QA Owner, quality checks either do not happen or are done inconsistently by whoever has time. The QA Owner makes quality a defined role, not an afterthought.

**What to do:**

- Each project PM nominates a QA Owner and a Backup QA Owner
- Criteria: someone who did not write the feature being tested; knows the product well; has time allocated for QA duties
- QA Owner rotation: every 2–3 months — the outgoing QA Owner briefs the incoming one
- The QA Owner runs the **async staging check** by 16:45 every day and posts a pass/fail result in the team channel (see Item 7 in the Daily Pulse)

```
QA Owner daily routine:
  16:30 → Run smoke test checklist on staging
  16:45 → Post result in team channel:
           ✓ PASS: "[Project] staging clear."
           ✗ FAIL: "[Project] issue: [description]. @[developer] please review."
  17:00 → PM proceeds to State of Product Confirmation
```

**Projects needing QA Owners:** Create Project, EMS, FOCUST, AI Phone Agent, SNS

**Owner:** Each project PM
**Deadline:** March 2026

> **Full reference:** Sections 6.3, 5.6 of the System Framework

---

## 4. Google Drive Folder Structure

**What it is:** A shared Google Drive folder structure that gives every team member a consistent place to find and store documents — SOPs, KPI sheets, meeting summaries, project files, and client communications.

**Why it matters:** Without a shared structure, documents are scattered across personal drives, Slack messages, and email threads. Knowledge that cannot be found is effectively lost.

**What to do:**

Set up the following top-level structure in the team Google Drive:

```
AIBOS Uganda (Shared Drive)
├── Operations/
│   ├── Templates/        ← All standard templates
│   ├── SOPs/             ← How-To guides for recurring tasks
│   ├── TSS Summaries/    ← Weekly Tech Sharing Session notes
│   └── KPI Tracking/     ← Google Sheets KPI dashboards
├── Projects/
│   └── [Project Name]/
│       ├── Client Comms/ ← Client-facing documents only
│       ├── Internal/     ← Internal project documents
│       └── Handover/     ← Shadow handover records
├── Teams/
│   ├── Frontend/         ← Skills map, department SOPs
│   └── Backend/          ← Skills map, department SOPs
└── Shared with Clients/  ← Copies shared externally
```

**Owner:** Product team (led by Management Owner)
**Deadline:** March 14, 2026

> **Full reference:** Section 11.4 of the System Framework

---

## 5. Shadow / Backup Assignments

**What it is:** Every project has a Primary lead and a Shadow. The Shadow stays informed enough to step in immediately if the Primary is unavailable — without a transition period or ramp-up delay.

**Why it matters:** When a key person is unavailable and there is no Shadow, the project stalls. A named Shadow prevents this from happening.

**What to do:**

- Management Owner and PMs confirm the Primary and Shadow for every active project
- Shadow responsibilities: attends the weekly product meeting; is CC'd on significant client communication; can give a 5-minute project status update at any time
- Document each assignment using the Shadow Handover template (stored in Google Drive under Operations/Templates/)

| Project | Primary Lead | Shadow |
| ------- | ------------ | ------ |
| Create Project | To be confirmed | To be confirmed |
| EMS | To be confirmed | To be confirmed |
| FOCUST | FOCUST PM | To be confirmed |
| AI Phone Agent | AI Phone Agent PM | To be confirmed |

**Owner:** Management Owner + PMs
**Deadline:** March 7, 2026

> **Full reference:** Section 10.2 of the System Framework

---

## 6. KPI Dashboard Activation

**What it is:** A Google Sheet where each PM logs daily operational metrics — client response violations, delay escalations, bugs caught, delivery status. The Management Owner reviews the summary tab every Tuesday at the PDMO meeting.

**Why it matters:** Without data, there is no way to know whether the framework is working or where the gaps are. The KPI dashboard turns daily activity into visible trends.

**What to do:**

- Management Owner sets up the Google Sheet with one tab per project and one summary tab
- Each PM begins filling their project row daily from **March 16 (Phase 2 start)** during the State of Product Confirmation (17:00)
- **Phase 2 is Observation Mode** — fill every cell honestly with the real number. There are no targets and no pressure during this phase. The goal is to establish a baseline.

**What to track (Phase 2 — observation only):**

| Metric | Fill daily with |
| ------ | --------------- |
| 15-min response violations | Number of times a client message was not acknowledged within 15 min |
| Delay risks escalated proactively | Yes / No / N/A |
| Pre-delivery bugs caught by QA | Number found before reaching client |
| Post-delivery bugs reported by client | Number reported by client |
| On-time delivery | Yes / No / Partial |

> **Note:** Automated KPI extraction is planned for Phase 4 (May 2026) to reduce manual entry and prevent data rot over time.

**Owner:** Management Owner (setup) + each PM (daily entry)
**Deadline:** Setup by March 1; daily logging begins March 16

> **Full reference:** Sections 4.1, 4.3 of the System Framework

---

## 7. Designated Weekly Communicator (DWC)

**What it is:** One named person per project is responsible for monitoring the client channel and sending the first acknowledgment within 15 minutes. This role rotates weekly. Everyone else on the team is not expected to watch the client channel.

**Why it matters:** When the whole team is responsible for client responses, no one feels individually accountable (bystander effect), and the 15-minute window gets missed. Constant channel monitoring also destroys deep-focus work for developers.

**What to do:**

- Each PM names the DWC for their project every Monday morning and announces it in the standup
- The DWC monitors the client channel during working hours and sends the first acknowledgment using the standard response templates (see below)
- The DWC does not need to solve the problem — they acknowledge it and route it to the right person
- The role excludes the QA Owner for that week (to keep QA focus clean)

**Response templates the DWC uses:**

*When you can answer immediately:*
> Direct, accurate answer to the client's question.

*When it will take up to 1 hour:*
> "Hi [Client], thank you for your message about [topic]. We are reviewing this now and will get back to you within the hour. — [Name]"

*When it will take until end of day:*
> "Hi [Client], thank you for reaching out about [topic]. We are looking into this and will include a full update in our end-of-day report. — [Name]"

**Owner:** Each project PM (confirms DWC weekly)
**Deadline:** March 2026 — begins Phase 2

> **Full reference:** Sections 3.3, 7.1 of the System Framework

---

## 8. Split EOD Report — Client vs. Internal

**What it is:** Two separate reports sent at 17:30 every working day — a concise Client EOD for the client, and a detailed Internal SitRep for management and the C-3 PMO.

**Why it matters:** A single report serving both audiences creates a problem: the client does not need GitHub issue numbers, KPI scores, or internal escalation details — and internal management does need exactly those things. A split report serves each audience correctly without adding significant PM effort.

**What to do:**

Send two reports by 17:30 each working day:

**Report 1 — Client EOD** (to the client channel):

```
Hello [Client Name],

Here is your daily update for [Day, Date].

PROGRESS TODAY
- [What was completed or moved forward — plain language]

NEXT STEPS
- [What the team is working on next]

RISKS / DELAYS
[ ] None at this time
OR: [Plain description of risk and what we are doing about it]

Best regards, [Name] | [Project]
```

**Report 2 — Internal SitRep** (to the Daily Reports internal channel):

```
INTERNAL SITREP — [Project] — [Day, Date]

1. DELIVERY STATUS
- Completed: [GitHub Issue # + description]
- In Progress: [GitHub Issue # + % complete]
- Blocked: [GitHub Issue # — blocker — owner]

2. KPI LOG
- Response violations: [number]
- Delay escalated proactively: [Yes/No/N/A]
- Pre-delivery bugs caught: [number]
- Client-reported bugs: [number]

3. RISKS / BLOCKERS
[ ] None  OR: [Risk — impact — mitigation — owner]

4. SUPPORT NEEDED
[ ] None  OR: [What, from whom, by when]
```

**Owner:** Each project PM
**Deadline:** March 16 — begins Phase 2

> **Full reference:** Sections 8.1, 8.2 of the System Framework

---

## 9. E2E Testing Framework — Playwright

**What it is:** Automated end-to-end tests that simulate real user actions and run automatically on every code push. Built using Playwright (open-source).

**Why it matters:** Code review (Layer 1) and smoke tests (Layer 2) catch many issues, but they cannot catch every regression — especially subtle ones that only appear when multiple parts of the system interact. Automated E2E tests build a growing safety net that gets stronger with every sprint.

**What to do:**

- Set up a basic Playwright structure in each project repository within one sprint (April)
- Start with the most critical user flows only — do not try to cover everything from day one
- Configure tests to run automatically on every code push as part of the PR pipeline
- Expand test coverage incrementally — each sprint adds tests for newly shipped features

**When automated tests become mandatory (the threshold):**

| Project Stage | Test Requirement |
| ------------- | ---------------- |
| MVP / Demo | No automated tests required |
| Beta | Core user flows must have at least basic E2E coverage |
| Production | All P0 and P1 features must have automated test coverage before deployment |

> **Note on current projects:** FOCUST and EMS are currently MVP/Beta-stage and rely heavily on exploratory testing. Playwright setup begins in April as part of Phase 3.

**Owner:** Development team (per project)
**Deadline:** April–May 2026 (Phase 3–4)

> **Full reference:** Sections 6.2 (Layer 4), 6.8 of the System Framework

---

## 10. AI Code Review Tool — Selection & Trial

**What it is:** An AI tool that automatically reviews every Pull Request for code quality, security issues, and common errors — before a human reviewer sees it.

**Why it matters:** It provides consistent, immediate feedback on every PR at near-zero time cost. It enforces the C-3 PMO rule that no PR is merged without a review, without requiring a human to be available for every routine change.

**What to do:**

- Evaluate three candidates: **CodeRabbit**, **GitHub Copilot code review**, **Graphite**
- Trial one tool for one full sprint across at least two projects
- Assess: Does it catch real issues? Are the comments actionable? What is the monthly cost?
- Decision by end of March — commit to one tool for Phase 2 onwards

**Decision criteria:**

| Criterion | What to assess |
| --------- | -------------- |
| Catch rate | Does it flag real bugs, not just style issues? |
| Signal-to-noise | Are the comments useful, or do developers learn to ignore them? |
| Integration | Does it connect cleanly to GitHub PRs? |
| Cost | Monthly subscription vs. value delivered |

**Owner:** Product Manager (evaluation) + Management Owner (final decision)
**Deadline:** March 2026

> **Full reference:** Section 6.8 of the System Framework

---

## 11. No Ticket, No Code — Enforcement

**What it is:** A rule — inherited from the C-3 PMO charter — that every piece of development work must have a GitHub Issue before any code is written. Every Pull Request must be linked to a GitHub Issue. No exceptions.

**Why it matters:** Code written without a ticket is invisible to the team, to management, and to the client. It cannot be tracked, reviewed, or reported on. It is the single most common source of scope creep and hidden work.

**What to do:**

- Every engineer checks: does a GitHub Issue exist for this work before writing any code?
- Every PR description must include a link to the corresponding GitHub Issue
- If no issue exists, the engineer creates one before opening the PR
- PMs audit compliance at the twice-weekly C-3 PMO check (Monday and Thursday)
- The Definition of Done checklist (Section 6.4 of main framework) includes this as the first gate

**Quick check — before writing any code:**

```
□  Does a GitHub Issue exist for this task?
     YES → proceed
     NO  → create the issue first, then proceed
□  Is the issue assigned to me with a deadline?
     YES → proceed
     NO  → confirm with PM before starting
```

**Owner:** All Engineers + PMs (audit) + Product Manager (enforcement)
**Deadline:** March 2026 — ongoing

> **Full reference:** Sections 6.4, 17.3 of the System Framework

---

> **This document is a companion to the full AIBOS Uganda System-Driven Delivery Framework (Version 3.0). All 11 items above are classified as Must-Do — meaning the framework cannot function as designed until they are complete. For full context, templates, and supporting detail on any item, refer to the section numbers noted above.**
