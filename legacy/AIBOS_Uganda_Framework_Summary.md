---
title: "AIBOS Uganda Framework"
header-includes: |
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap');
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
    html, body {
      background: #ffffff;
      font-family: 'Inter', -apple-system, sans-serif;
      font-size: 11pt; line-height: 1.75; color: #1a1f36;
      width: 100%; max-width: none;
    }

    /* ── EACH SLIDE = section.level2 ── */
    section.level2 {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      padding: 48px 52px;
      page-break-before: always;
      page-break-inside: avoid;
    }
    section.level2:first-of-type {
      page-break-before: avoid;
      background: #1a1f36;
      color: #ffffff;
      justify-content: center;
      align-items: flex-start;
    }

    /* ── TITLE SLIDE OVERRIDES ── */
    section.level2:first-of-type {
      padding: 64px 60px;
    }
    section.level2:first-of-type h2 {
      font-size: 42pt; font-weight: 800; color: #ffffff;
      background: none; border: none; padding: 0;
      margin-bottom: 6px; letter-spacing: -0.03em;
      white-space: nowrap; line-height: 1.1;
    }
    section.level2:first-of-type h3 {
      color: #7c93f5; font-size: 13pt; text-transform: none;
      letter-spacing: 0.01em; border: none; padding: 0;
      margin-top: 0; margin-bottom: 36px; font-weight: 300;
    }
    section.level2:first-of-type p {
      color: #c5cbf9; font-size: 10.5pt;
      padding: 0; margin-bottom: 8px; max-width: 580px;
    }
    section.level2:first-of-type blockquote {
      background: rgba(59,91,219,0.2);
      border-left: 4px solid #3b5bdb;
      border-top: none; border-right: none; border-bottom: none;
      padding: 14px 20px; margin: 32px 0 0 0;
      max-width: 600px;
    }
    section.level2:first-of-type blockquote p {
      color: #e0e6ff; font-style: italic; margin: 0;
    }
    section.level2:first-of-type hr {
      border-color: rgba(255,255,255,0.12); margin: 28px 0;
    }
    section.level2:first-of-type strong { color: #ffffff; }
    section.level2:first-of-type em { color: #9aaaf5; font-style: normal; font-size: 9pt; }

    /* ── SLIDE HEADINGS ── */
    h2 {
      font-size: 20pt; font-weight: 800; color: #1a1f36;
      border-left: 6px solid #3b5bdb;
      padding: 4px 0 4px 18px;
      margin-bottom: 28px;
      page-break-before: avoid; page-break-after: avoid;
      letter-spacing: -0.01em;
    }

    /* ── SECTION LABELS ── */
    h3 {
      font-size: 8.5pt; font-weight: 700; color: #3b5bdb;
      text-transform: uppercase; letter-spacing: 0.1em;
      border-bottom: 1px solid #dce2f5; padding-bottom: 5px;
      margin-top: 26px; margin-bottom: 10px;
      page-break-after: avoid;
    }

    /* ── BODY ── */
    p { margin-bottom: 11px; orphans: 3; widows: 3; }
    ul, ol { margin: 6px 0 14px 22px; }
    li { margin-bottom: 5px; }
    strong { font-weight: 700; }
    hr { border: none; border-top: 1px solid #dce2f5; margin: 22px 0; }

    /* ── CALLOUT BOX ── */
    blockquote {
      background: #f0f4ff;
      border-left: 5px solid #3b5bdb;
      border-top: 1px solid #c5cbf9;
      border-right: 1px solid #c5cbf9;
      border-bottom: 1px solid #c5cbf9;
      padding: 13px 18px; margin: 18px 0; color: #1a1f36;
    }
    blockquote p { margin: 0; }
    blockquote strong { color: #3b5bdb; }

    /* ── DIAGRAMS ── */
    pre {
      background: #1a1f36; color: #c0caf5;
      padding: 16px 20px; margin: 14px 0;
      font-family: 'Courier New', monospace;
      font-size: 8pt; line-height: 1.65;
      page-break-inside: avoid;
      border-left: 4px solid #3b5bdb;
    }
    pre code { background: transparent; color: inherit; padding: 0; border: none; }
    code {
      background: #eef0fb; color: #364fc7;
      padding: 2px 6px; font-size: 8.5pt;
      border: 1px solid #c5cbf9;
      font-family: 'Courier New', monospace;
    }

    /* ── TABLES ── */
    table {
      width: 100%; border-collapse: collapse; margin: 14px 0;
      font-size: 9.5pt; page-break-inside: avoid;
      border: 1px solid #c8cfe8;
    }
    thead tr { background: #3b5bdb; color: #ffffff; }
    thead th {
      padding: 9px 13px; text-align: left; font-weight: 600;
      font-size: 9pt; border-right: 1px solid #2d4bb5;
    }
    thead th:last-child { border-right: none; }
    tbody tr { border-bottom: 1px solid #c8cfe8; }
    tbody tr:nth-child(even) { background: #f5f7fc; }
    tbody tr:last-child { border-bottom: none; }
    td { padding: 8px 13px; vertical-align: top; border-right: 1px solid #e2e6f0; }
    td:last-child { border-right: none; }

    header#title-block-header { display: none; }
  </style>
---

## AIBOS Uganda
### System-Driven Delivery Framework

A summary of the full operational framework — how we work every day, how we ensure quality, how we communicate, and how we grow as an organisation.

**Prepared for:** All team members — developers, product managers, and leadership

**Reference document:** Full version available on Google Drive · Questions: B1 Channel

---

> **Core belief:** When the system is strong, the team delivers consistently — regardless of who is present on any given day.

*Version 2.0 — February 2026*

## 1. The Problem We're Solving

Every growing product team eventually hits the same wall. Delivery becomes unpredictable. Communication gaps open up between teams and clients. Quality fluctuates from one sprint to the next. The instinctive response is to hire better people or work harder — but the root cause is almost always structural: **the team is running on people, not systems.**

When delivery depends on individuals, the organisation is only as reliable as its most available, most organised, most knowledgeable person on any given day. That is not a foundation for consistent growth. At AIBOS Uganda, we identified four specific patterns that were holding us back — and each one pointed to the same underlying gap: the absence of shared, repeatable systems.

1. **Person-locked knowledge** — critical context lived in a few people's heads. When they were unavailable, progress stalled and decisions were delayed, sometimes for days
2. **Inconsistent quality** — without a shared definition of "done", quality was determined by individual judgment rather than a common standard, leading to variable client experiences
3. **Reactive communication** — clients and management received updates when someone remembered or felt they had enough to say, not on a defined cadence, which eroded trust over time
4. **No shared visibility** — blockers and risks were invisible to the wider team until they escalated into emergencies, making prevention nearly impossible

---

| Before — Person-Dependent | After — System-Driven |
| ---------------------------------------------- | ------------------------------------------ |
| Quality depends on specific individuals | Quality is enforced by the system |
| Communication happens when someone remembers | Communication follows a defined protocol |
| Decisions live in people's heads | Decisions are documented and accessible |
| Knowledge is lost when someone is unavailable | Knowledge lives in documentation and tools |
| Managers spend time firefighting | Managers monitor, guide, and continuously improve |

## 2. Our Response — The 7 Pillars

The framework is built on **seven interconnected pillars**. Each pillar addresses a specific failure mode identified in the team's current operation. They are not independent initiatives — they reinforce one another. Strong standards make quality enforceable. A consistent daily rhythm makes standards visible. Good documentation makes continuity possible. Together, they create a delivery system that any team member can operate and any new hire can step into from day one.

---

**1. Standards**
Defined, measurable expectations for response time, quality gates, and delivery timelines. Standards remove ambiguity — nobody interprets "good enough" differently, and nobody needs to ask what is expected of them. They are the baseline that every other pillar is built on.

**2. Operations — The Daily Pulse**
A structured daily rhythm — morning alignment, focused work, evening review, EOD report — that keeps every team coordinated without constant management intervention. The Daily Pulse means the team self-organises around a shared cadence rather than waiting to be directed.

**3. Quality Assurance**
A 4-layer QA filter with a named, rotating QA Owner on every project. Each layer catches a different class of defect. The goal is that bugs are found and fixed internally — never by the client. Quality is the system's output, not any individual's personal effort.

**4. Communication Protocol**
Every message, update, and escalation follows one of three defined paths based on urgency and impact. The 15-minute acknowledgement window sets the client expectation, and the escalation path ensures that no risk travels silently until it becomes a crisis.

**5. Knowledge Management**
Two complementary systems — Google Drive for organisational knowledge (SOPs, templates, KPIs) and GitHub `/docs` per project for technical documentation. The rule is simple: if it is not written down, it is not a standard. Undocumented knowledge is a liability, not an asset.

**6. People & Continuity**
Shadow and backup roles ensure every project can continue without interruption when a team member is unavailable. Skills mapping helps PMs assign the right work to the right people. A built-in recognition system reinforces the behaviours the team needs to sustain.

**7. Technology**
Shared AI tools and development environments give the team access to powerful capability at a manageable cost. Rather than each team member purchasing individual subscriptions, a centralised shared model maximises value and keeps tooling consistent across teams.

## 3. The Daily Rhythm — The Daily Pulse

The Daily Pulse is the operational heartbeat of AIBOS Uganda. It runs **every working day without exception** — not because it is enforced, but because it replaces the informal coordination that previously depended on individuals remembering to communicate. Each touchpoint in the day has a clear purpose, a defined owner, and a maximum time limit. The morning loop surfaces blockers before they cost hours. The evening loop closes the day with documented status so no information is lost overnight.

```
MORNING LOOP
──────────────────────────────────────────────────────────────────
 09:00   COMPANY STANDUP  (10 min — all teams)
         3 questions per person:
         What did I do? | What will I do today? | Any blockers?
         ↓
 09:10   TEAM PREP MEETING  (10 min — PM + team)
         Technical alignment. Task ownership confirmed. Dependencies checked.
         ↓
 09:20   PM → MANAGEMENT OWNER SYNC  (as needed — urgent items only)
         Management Owner aware of all critical risks before 09:30.

WORK DAY
──────────────────────────────────────────────────────────────────
         Teams execute. PMs monitor. Blockers escalated immediately.
         Client responses follow the 15-minute acknowledgement protocol.

EVENING LOOP
──────────────────────────────────────────────────────────────────
 16:30   TEAM PEER REVIEW  (30 min)
         Staging environment reviewed. QA Owner runs smoke test checklist.
         ↓
 17:00   STATE OF PRODUCT CONFIRMATION
         PM confirms: what is done / at risk / needs escalation
         ↓
 17:15   MANAGEMENT MEETING
         Company-wide daily status. Unresolved blockers. Decisions made.
         ↓
 17:30   EOD REPORT posted to the team channel
         Audience: Client + Internal Management
──────────────────────────────────────────────────────────────────
```

> **Why it works:** Every risk surfaced in the morning gets a decision before 09:30. Every risk that emerges during the day is visible to management by 17:15. No blocker survives more than one working cycle without an owner and a response. The EOD report at 17:30 means the client always has a written update — removing the anxiety of silence and building a paper trail that protects both the team and the relationship.

## 4. Standards & KPIs — What We Measure

Standards without measurement are intentions. The SLA framework defines the non-negotiable behaviours, and the KPI dashboard makes them visible — so the team can see progress, management can spot gaps early, and Japan leadership has real-time confidence in Uganda's operations.

### The 5 SLA Standards — Non-Negotiable

- **15-minute response** — client messages must be acknowledged within 15 minutes during work hours. Not resolved — *acknowledged*. Silence is interpreted as disengagement; a quick acknowledgement buys time and preserves trust.
- **Proactive delay communication** — any risk to a deadline must be escalated *before* the deadline passes. A late warning is not a warning — it is a failure. Clients need time to adjust, not just an apology.
- **Immediate bug logging** — all bugs are logged in the KPI sheet the moment they are found. Verbal-only reports disappear; written records create accountability and patterns that drive systemic improvement.
- **Documentation first** — if a task is done more than twice, it must have a written How-To. Undocumented practices are personal habits, not team standards — they cannot be reviewed, improved, or handed over.
- **Structured meetings** — every meeting has a pre-shared agenda and closes with written action items, owners, and deadlines. Meetings without these produce conversation, not progress.

---

### KPI Dashboard — Weekly Tracking

| Metric | Target | Why It Matters |
| -------------------------------------- | ------- | --------------------------------- |
| 15-min client response compliance | 100% | Trust is built in small moments |
| Delay risks escalated proactively | 100% | Early warning enables early action |
| Bugs caught before client sees them | 90%+ | Internal quality protects reputation |
| Post-delivery bugs (client-reported) | 0 | Zero tolerance for avoidable failures |
| On-time delivery | 100% | Reliability is the core commitment |

Each PM fills their project row in the shared Google Sheet **every evening**. The Management Owner reviews the full summary every **Tuesday at the PDMO meeting**. Japan leadership (Prakhar and Nate) has view access at all times — meaning performance is transparent up the chain without requiring a separate reporting layer.

## 5. The Quality System — 4 Layers

Quality is not one person's responsibility — it is the system's output. A single QA Owner or a single review step is a single point of failure. The 4-layer model distributes quality assurance across the team, with each layer designed to catch what the previous one might miss. When a bug reaches the client, the question is never *who wrote it* — it is *which layer failed to catch it*, and what needs to change to prevent the same gap in the future.

```
  ┌────────────────────────────────────────────────────────────┐
  │  LAYER 1 — PEER REVIEW                                     │
  │  Developer reviews a teammate's work before it is merged.  │
  │  Focus: logic, edge cases, coding standards                │
  └───────────────────────────┬────────────────────────────────┘
                              ↓  Passes
  ┌────────────────────────────────────────────────────────────┐
  │  LAYER 2 — QA OWNER SMOKE TEST                             │
  │  Named QA Owner runs structured checklist on every         │
  │  staging deployment. Signs the Definition of Done.         │
  └───────────────────────────┬────────────────────────────────┘
                              ↓  Passes
  ┌────────────────────────────────────────────────────────────┐
  │  LAYER 3 — CROSS-TEAM REVIEW                               │
  │  Another team tests the feature as a real user would.      │
  │  Focus: usability, integration, unexpected behaviour       │
  └───────────────────────────┬────────────────────────────────┘
                              ↓  Passes
  ┌────────────────────────────────────────────────────────────┐
  │  LAYER 4 — AUTOMATED TESTS                                 │
  │  Unit and integration tests run on every code push.        │
  │  Focus: regressions, edge cases                            │
  └───────────────────────────┬────────────────────────────────┘
                              ↓  All 4 layers pass
                    APPROVED FOR PRODUCTION
```

> **The rule:** Nothing moves to production without passing all 4 layers. A **QA Owner** is nominated for every project by March 1 and rotates every 2–3 months — keeping the role fresh and preventing quality oversight from becoming routine or overlooked. The QA Owner is accountable for the checklist, but quality itself remains everyone's shared responsibility.

## 6. Communication & Meetings

Unstructured communication is one of the most common sources of delay and misalignment in product teams. Messages sent to the wrong channel, escalations that arrive too late, and meetings that produce no clear decisions — these are not people problems, they are system problems. The communication framework at AIBOS Uganda defines exactly how information flows: who receives it, through which channel, within what timeframe, and to what outcome.

### How Communication Is Routed — 3 Paths

Every issue, update, or concern at AIBOS Uganda falls into one of three clearly defined paths. This prevents both under-communication (silence when action is needed) and over-escalation (interrupting management with things that can wait). The path is determined by two questions: is it urgent, and is it blocking delivery?

```
  Is this urgent and blocking delivery?
           │
     YES ──┤                        NO
           │                         │
  Respond directly           Is it time-sensitive?
  within 15 minutes                  │
  Path A: Direct answer        YES ──┤          NO
                                     │           │
                             Escalate        Queue for
                             same day        weekly PDMO
                             Path B          Path C
```

### The Weekly Meeting Structure

| When | Meeting | Led By | Duration |
| ------------- | ---------------------------------- | -------------------- | -------- |
| Mon–Fri 09:00 | Company Standup | GA | 10 min |
| Tuesday 14:00 | **PDMO — All PMs Sync** | **Management Owner** | **30–45 min** |
| Friday | **Technical Sharing Session (TSS)** | **Assigned team** | **30 min** |
| Daily 17:30 | EOD Report (written, to channel) | PM per project | — |

**PDMO every Tuesday** is the management layer's primary alignment point. It brings all Product Managers together with the Management Owner to review project status, address cross-team dependencies, resolve issues that could not be handled at the PM level, and close with team recognition. It is where the week's operational picture becomes clear.

**TSS every Friday** is the team's investment in its own capability. One team presents a technical topic — a tool, a solution, a lesson learned — and the rest of the team engages. Attendees are urged to ask questions to deepen cross-team learning. The session summary is saved to Google Drive within 24 hours, turning individual knowledge into shared organisational capital. TSS content also feeds into external technical blogs, building AIBOS Uganda's presence beyond the immediate client work.

## 7. Knowledge, People & Continuity

Knowledge that lives only in someone's head is not an asset — it is a risk. The moment that person is unavailable, on leave, or transitions out of a role, the organisation loses capability it cannot easily recover. The knowledge management system at AIBOS Uganda is designed to make information accessible, searchable, and maintained — so that any team member can find what they need without having to ask a specific individual.

### Two-Tier Knowledge System

```
  ORGANISATIONAL KNOWLEDGE                TECHNICAL KNOWLEDGE
  ─────────────────────────               ──────────────────────────
  Google Drive (Shared)                   GitHub /docs (per project)
  ├── Operations/                         ├── 1-planning/
  │   ├── Templates/     ← Frameworks     │     requirements, features
  │   ├── SOPs/          ← How-To guides  ├── 2-design/
  │   ├── TSS Summaries/ ← Session notes  │     architecture, decisions
  │   └── KPI Tracking/  ← Dashboards    ├── 3-execution/
  ├── Projects/                           │     weekly checks, gates
  │   └── [Name]/                        └── 4-delivery/
  │       ├── Client Comms/                    handover, changelog
  │       ├── Internal/
  │       └── Handover/
  └── Teams/             ← Skills maps
```

### The Shadow / Backup System

Every project has a **Primary** lead and a **Shadow**. The Shadow is not a passive backup — they attend weekly product meetings, stay current on project status, and maintain enough context to step in immediately without a transition period. This is not about distrust; it is about resilience. Any team is more reliable when continuity is built in by design rather than scrambled for in a crisis.

### Built-In Recognition

Motivation is not left to chance. Recognition is structured into the weekly rhythm so that good work is consistently noticed and named — not just in moments of crisis, but in the ordinary flow of delivery.

- **Every Tuesday PDMO** — Team Highlight: one specific shoutout for exemplary SLA/KPI performance that week, shared with the full team
- **Every Tuesday PDMO** — Under-the-Radar contribution: nominated quiet wins that would otherwise go unnoticed — the fix made at midnight, the documentation written proactively, the teammate unblocked without being asked
- **Monthly** — top KPI performer acknowledged by the Management Owner and noted in the Japan summary report
- **Quarterly** — TSS contributor of the quarter recognised by leadership as an investment in the team's collective growth

> **The rule:** If a task is done more than twice, it must have a written How-To. If it is not documented, it is a personal habit — not a team standard. Standards can be reviewed, improved, and handed over. Habits cannot.

## 8. Delivery Stages & The Rollout Plan

Every client request, regardless of size, enters the same intake process and moves through the same defined stages before reaching production. This structure prevents scope ambiguity at the start, controls deployment risk in the middle, and protects the client relationship at the end. Each stage has clear entry and exit criteria — a project does not advance until it has earned the right to.

### How a Project Moves From Request to Production

```
  CLIENT REQUEST
        │
        ↓
  INTAKE REVIEW  (Management Owner + PM)
  Scope confirmed. Phase assigned. Team briefed. G1 gate: requirements documented.
        │
   ┌────┴──────────────────────────────────────┐
   ↓                                           ↓
 ┌──────────────┐   ┌──────────────┐   ┌──────────────────────┐
 │     MVP      │ → │     BETA     │ → │     PRODUCTION       │
 │              │   │              │   │                      │
 │ Core only.   │   │ Stable and   │   │ Full deployment.     │
 │ No polish.   │   │ tested with  │   │ All 4 QA layers      │
 │ Validated    │   │ limited      │   │ passed. DoD signed.  │
 │ with real    │   │ users.       │   │ Client confirmed.    │
 │ users first. │   │ Feedback     │   │                      │
 │              │   │ loop active. │   │                      │
 └──────────────┘   └──────────────┘   └──────────────────────┘
```

### The 4-Phase Implementation Rollout

The rollout is intentionally phased — not to delay, but to build lasting adoption. Each phase serves a distinct purpose: lay the foundation, stress-test it in practice, prove it with data, then build on it strategically.

| Phase | Window | What Happens |
| ----------------------- | --------------- | ---------------------------------------------------- |
| **1 — Foundation** | Feb 23 – Mar 15 | Ownership assigned. KPI sheet built. Team briefed on all systems. Google Drive structured. QA Owners nominated. |
| **2 — Trial** | Mar 16 – Mar 31 | The full system runs for the first time. Friction points are identified without judgement and addressed before April. |
| **3 — Proving** | Apr 1 – Apr 30 | Adoption is measured, not assumed. KPI data tells the real story. Confidence grows from evidence, not intention. |
| **4 — Strategy** | May onwards | AI tools integrated into the shared environment. Skills-based hiring begins. The team scales on a proven foundation. |

### What Success Looks Like by End of Phase 3

These are the measurable signals that the system has taken root — not just been introduced.

- Client response violations trending consistently toward zero
- 80%+ of delay risks are escalated proactively, before the deadline passes
- Client-reported post-delivery bugs are significantly reduced from the pre-framework baseline
- KPI sheet is filled at a 90%+ completion rate, showing team ownership of the data
- The team is able to operate fully and confidently without the Management Owner present for a full working day

---

> **This is our plan — and it starts with all of us.** Building a system-driven organisation is not a single decision made in a meeting — it is a daily practice built in small, consistent actions. Every team member who follows the Daily Pulse, fills the KPI sheet, and communicates proactively is contributing to something larger than their individual role: an organisation that delivers reliably, grows deliberately, and does not depend on any one person to function. The goal is not perfection from day one. It is honest progress, shared accountability, and a team that gets measurably better every month.
