# AIBOS Uganda: System-Driven Delivery Framework
### A Comprehensive Plan for Quality, Communication, and Operational Excellence

---

> **"From a person-dependent organization to a system-driven organization."**

---

## Table of Contents

- [Section 0 — Executive Summary](#section-0--executive-summary)
- [Section 1 — Background & Context](#section-1--background--context)
- [Section 2 — Organizational Structure & Roles](#section-2--organizational-structure--roles)
- [Section 3 — SLA Framework](#section-3--sla-framework)
- [Section 4 — KPI Framework](#section-4--kpi-framework)
- [Section 5 — Daily Operational System (The Daily Pulse)](#section-5--daily-operational-system-the-daily-pulse)
- [Section 6 — Quality Assurance System](#section-6--quality-assurance-system)
- [Section 7 — Communication Protocol](#section-7--communication-protocol)
- [Section 8 — Reporting System](#section-8--reporting-system)
- [Section 9 — Meeting Structure & Schedule](#section-9--meeting-structure--schedule)
- [Section 10 — Capacity Building & Continuity](#section-10--capacity-building--continuity)
- [Section 11 — Documentation & Knowledge Management](#section-11--documentation--knowledge-management)
- [Section 12 — Reward & Motivation System](#section-12--reward--motivation-system)
- [Section 13 — MVP to Production Framework](#section-13--mvp-to-production-framework)
- [Section 14 — Implementation Roadmap](#section-14--implementation-roadmap)
- [Appendices](#appendices)

---

## Section 0 — Executive Summary

### Purpose

This document is the operational blueprint for AIBOS Uganda's transformation from a person-dependent delivery model into a system-driven organization. It consolidates all agreed frameworks, processes, standards, and tools into a single reference that any team member — current or new — can use to understand how we work, what is expected, and how to contribute effectively.

### The Core Transformation Goal

| From | To |
|---|---|
| Quality depends on specific individuals | Quality is enforced by the system |
| Communication happens when someone remembers | Communication follows a defined protocol |
| Decisions live in people's heads | Decisions are documented and accessible |
| Managers spend time firefighting | Managers monitor, guide, and improve the system |
| Knowledge is lost when someone leaves | Knowledge lives in documentation and tools |

### What This Document Covers

This framework addresses six interconnected pillars:

1. **Standards** — SLAs, KPIs, and measurable expectations
2. **Operations** — Daily routines, meetings, and reporting
3. **Quality** — QA layers, ownership, and release governance
4. **Communication** — Client and internal communication protocols
5. **Knowledge** — Documentation, templates, and Aibos Atlas
6. **People** — Capacity building, continuity, and recognition

### How to Use This Document

- **New team members:** Read Sections 1–5 first for full context, then refer to specific sections as needed
- **Product Managers:** Sections 5, 6, 7, 8, and 9 are your primary operational reference
- **Developers:** Sections 6, 7, and 13 are most relevant to your daily work
- **Leadership:** Sections 2, 3, 4, and 14 provide governance and strategic overview

---

## Section 1 — Background & Context

### 1.1 The Challenge: Client Feedback

AIBOS Uganda received structured feedback from client DATAGRID that highlighted recurring process gaps. These gaps are not unique to DATAGRID — they reflect systemic issues across all AIBOS Uganda operations, including internal projects. AIBOS Japan is also considered a client of AIBOS Uganda.

**Quality Issues Identified:**

- Deliverables submitted at a quality level that would not pass Japanese review standards
- Bugs that would be caught by basic testing are reaching the client
- Over-engineering beyond MVP scope — building features the client did not ask for

**Communication Issues Identified:**

- Tasks started based on misunderstood requirements
- Slow responses to client questions
- Deadlines not confirmed before work begins
- Task delays communicated on the due date rather than in advance
- Previously identified mistakes being repeated

### 1.2 The Root Cause: Person-Dependency

The underlying cause of these issues is not a lack of skill or knowledge. The root cause is structural:

> **The organization currently relies too heavily on specific individuals to maintain quality and communication standards. When those individuals are busy, unavailable, or overloaded, standards drop.**

This creates two problems:
- Talented individuals carry an unsustainable personal burden
- The organization cannot scale because performance is tied to people, not systems

### 1.3 The Goal

```
Current State                          Target State
─────────────────────────────────────────────────────
Talented individual carries quality    System enforces quality
Manager fixes every problem            Process prevents problems
Knowledge lives in one person          Knowledge lives in documentation
Communication depends on memory        Communication follows protocol
─────────────────────────────────────────────────────
```

### 1.4 What This Is and Is Not

| This IS | This is NOT |
|---|---|
| A process and systems initiative | Punishment or blame for any individual |
| A collective effort across all levels | A performance review mechanism |
| An opportunity to build better systems | A criticism of individual capability |
| A foundation for AI-enabled growth | A set of rules imposed from the top down |

### 1.5 Guiding Mindset

| Principle | Meaning in Practice |
|---|---|
| **Mistakes are opportunities** | Every problem found is a chance to build a system that prevents it from recurring |
| **DRY (Don't Repeat Yourself)** | Once a mistake happens, we build a system so it never happens again |
| **Team over individual** | "Assignee" means "Owner" — the owner's job includes asking the team for help |
| **Standards over individuals** | If a process works for one person, document it so it works for everyone |
| **Japan-Uganda as one team** | Different contexts, same goal — building a company of global standard |

---

## Section 2 — Organizational Structure & Roles

### 2.1 Responsibility Model

There are two types of responsibility in every activity:

| Role | Description | Example |
|---|---|---|
| **Management Owner** | Bears ultimate responsibility. Assigns and oversees Execution Owners. Responsible for the system succeeding. | A manager who owns the meeting process — even if someone else facilitates |
| **Execution Owner** | Fulfills responsibility within their defined scope. Accountable for their piece of delivery. | A PM who facilitates the standup as the Execution Owner of that meeting |

**Key principle:** The Execution Owner is responsible for doing the work. The Management Owner is responsible for making sure the work gets done — including asking for help, removing blockers, and ensuring quality.

### 2.2 Initiative Ownership Structure

| Role | Person | Scope |
|---|---|---|
| **Management Owner** | Ambrose | Overall ownership of SLA/KPI improvement initiative |
| **Execution Owners** | Martin, Joseph, and Project PMs | Implementation and day-to-day execution |
| **Advisor — Development** | Prakhar (Head of Development, AIBOS Japan) | Guidance on development process and rule changes |
| **Advisor — Operations** | Nate (Head of AIBOS Uganda) | Guidance on Uganda structure and communication matters |

### 2.3 Japan-Uganda Leadership Responsibilities

| Leader | Ultimate Responsibility |
|---|---|
| Prakhar | Bridging the client and development team; approving development process changes |
| Nate | Overall Uganda structure and operational functioning |
| Ambrose | Day-to-day management of the SLA/KPI system and delivery standards |

### 2.4 Communication Channels

```
Type of Communication              Channel / Person
───────────────────────────────────────────────────────
General questions and discussions  B1 Channel (visible to all)
Communication-related matters      Consult Nate
Development process / rule changes Consult Prakhar
Project-level daily updates        Daily Reports Channel
Client communication               Per project PM, following protocol
───────────────────────────────────────────────────────
```

> **Note:** The B1 channel is the default for transparency. Direct messages should be used only for sensitive matters — everything operational should be visible to the team.

---

## Section 3 — SLA Framework

### 3.1 Overview

Service Level Agreements (SLAs) define the minimum standards of behavior expected from every team member. They are not guidelines — they are commitments. Meeting SLAs consistently is what builds trust with clients and within the team.

### 3.2 SLA Standards

| Area | Standard | Why It Matters |
|---|---|---|
| **Client Response Time** | First response within **15 minutes** during working hours | Eliminates client anxiety about being ignored; builds trust |
| **Deadline Management** | Escalate delay risks **immediately upon recognition** — never on the due date | Gives the client and team time to adjust; prevents surprise failures |
| **Requirements & Scope** | Confirm understanding **in writing** before starting work; MVP scope first | Eliminates work based on assumptions; prevents over-engineering |
| **Quality Assurance** | Two-stage check: **developer self-test → QA Owner verification** before any client delivery | Stops preventable bugs from reaching the client |
| **Meeting Management** | **Pre-assign roles**; share decisions and next actions **same day** | Ensures meetings produce outcomes, not just discussions |

### 3.3 SLA Monitoring

- SLA adherence is observed through the daily KPI log (see Section 4)
- Violations are not punitive — they are data points for system improvement
- Recurring violations in the same area trigger a process review

---

## Section 4 — KPI Framework

### 4.1 KPI Definitions

| KPI | What It Measures | Good Result |
|---|---|---|
| **15-min response violations** | Number of times a client message went unacknowledged for more than 15 minutes | 0 per week |
| **Delay escalation rate** | Percentage of delay risks shared proactively (before the due date) | 100% |
| **Pre-delivery bugs found in QA** | Number of bugs caught internally before reaching the client | Track trend downward |
| **Post-delivery bugs reported by client** | Number of bugs the client found after delivery | 0 target |
| **On-time delivery rate** | Percentage of tasks delivered on or before the agreed deadline | 100% target |

### 4.2 Collection & Review Cadence

| KPI | Collected | Reviewed |
|---|---|---|
| 15-min response violations | Daily (PM logs per project) | Weekly (PDMO meeting) |
| Delay escalation rate | Daily (PM logs per project) | Weekly (PDMO meeting) |
| Pre-delivery bugs found in QA | Daily (QA Owner logs) | Weekly (PDMO meeting) |
| Post-delivery bugs (client reported) | Daily (PM logs) | Weekly (PDMO meeting) |
| On-time delivery rate | Weekly (PM confirms) | Weekly (PDMO meeting) |

### 4.3 KPI Dashboard

**Tool:** Google Sheets (Phase 1) → Aibos Atlas Dashboard (Phase 2)

**Structure — One Sheet per Project, One Summary Tab:**

| KPI | Mon | Tue | Wed | Thu | Fri | Weekly Total | Target |
|---|---|---|---|---|---|---|---|
| 15-min response violations | | | | | | | 0 |
| Delay risks escalated proactively | | | | | | | 100% |
| Pre-delivery bugs found in QA | | | | | | | Log & trend |
| Post-delivery bugs (client) | | | | | | | 0 |
| On-time delivery | | | | | | | 100% |

**Rules:**
- Each PM fills their project's row during the **evening retrospective**
- Ambrose reviews the full summary tab every **Friday** in the PDMO meeting
- Japan team (Prakhar/Nate) has view access at all times
- An empty cell by EOD is flagged as a potential gap

**Summary Tab Format:**

| Project | Response SLA | Delay Escalation | Pre-delivery Bugs | Client Bugs | On-time Rate | Overall |
|---|---|---|---|---|---|---|
| Create Project | | | | | | 🟢/🟡/🔴 |
| EMS | | | | | | |
| FOCUST | | | | | | |
| AI Phone Agent | | | | | | |

---

## Section 5 — Daily Operational System (The Daily Pulse)

### 5.1 Overview

The Daily Pulse is the operational heartbeat of AIBOS Uganda. It ensures every working day begins with alignment and ends with validated progress. It is structured as two loops — a morning setup loop and an evening validation loop.

### 5.2 The Daily Pulse Flow

```
MORNING LOOP
─────────────────────────────────────────────────────────────────────
09:00 │ COMPANY STANDUP (6–10 min)
      │ All teams. High-level alignment on the day.
      │ Focus: priorities, blockers, team spirit
      ▼
09:10 │ TEAM PREPARATION MEETING (10 min)
      │ Each team internally. Led by the PM.
      │ Focus: technical alignment, task clarity, who owns what
      ▼
09:20 │ PM → MANAGEMENT OWNER SYNC
      │ PMs report urgent blockers to Ambrose.
      │ Focus: anything that needs management attention before the day runs
      │ Output: Ambrose aware of all critical risks before 09:30
─────────────────────────────────────────────────────────────────────

WORK DAY
─────────────────────────────────────────────────────────────────────
      │ Teams execute. PMs monitor. Blockers escalated immediately.
      │ Client responses follow the 15-min protocol (Section 7).
─────────────────────────────────────────────────────────────────────

EVENING LOOP
─────────────────────────────────────────────────────────────────────
16:30 │ TEAM PEER REVIEWS (30 min)
      │ Led by PM. All team members.
      │ Focus: review staging environment, cross-check each other's work
      │ QA Owner runs smoke test checklist
      ▼
17:00 │ STATE OF PRODUCT CONFIRMATION
      │ PM confirms product status for the day
      │ Focus: what is done, what is at risk, what needs escalation
      ▼
17:15 │ MANAGEMENT "BIG 3" MEETING
      │ Ambrose, Martin, Joseph
      │ Focus: company-wide daily status, unresolved blockers, decisions
      ▼
17:30 │ EOD REPORT TO CHANNEL
      │ PM posts standardized daily report
      │ Audience: Client + Internal Management
─────────────────────────────────────────────────────────────────────
```

### 5.3 Morning Standup Guidelines

- Maximum 10 minutes — no problem-solving in the standup
- Each person answers: What did I do? What will I do today? Any blockers?
- Blockers are noted and addressed in the PM sync that follows

### 5.4 Team Preparation Meeting Guidelines

- Maximum 10 minutes
- Led by the Project PM
- Technical focus: task ownership, dependencies, environment status
- Output: every team member knows their exact task for the day

### 5.5 PM → Management Owner Sync

- Brief and focused — only urgent items
- PMs report: anything that could affect client delivery, deadlines, or team capacity
- Ambrose makes immediate decisions on anything critical
- Non-urgent items go to the PDMO weekly meeting

---

## Section 6 — Quality Assurance System

### 6.1 Philosophy

Quality is not an individual's responsibility — it is the system's output. When a bug reaches the client, the question is not "who wrote the bug?" but "which layer of the QA system failed to catch it?"

The goal is to make it structurally difficult for poor quality to reach the client.

### 6.2 The 4-Layer QA Filter

```
CODE WRITTEN BY DEVELOPER
         │
         ▼
┌─────────────────────────┐
│  LAYER 1: PEER REVIEW   │  Developer's code is reviewed by a
│  (Daily)                │  peer before any merge.
│  Who: Team members      │  Focus: logic, standards, edge cases
└────────────┬────────────┘
             │ Passes
             ▼
┌─────────────────────────┐
│  LAYER 2: SMOKE TEST    │  PM or backup member runs a standard
│  (Per Deployment)       │  checklist of critical features.
│  Who: QA Owner / PM     │  Focus: "Does the core still work?"
└────────────┬────────────┘
             │ Passes
             ▼
┌─────────────────────────┐
│  LAYER 3: CROSS-TEAM    │  PM from another team tests the
│  EXPLORATORY TEST       │  product with fresh eyes.
│  (Weekly — PDMO)        │  Focus: UI, user flow, unexpected bugs
│  Who: Other PMs         │
└────────────┬────────────┘
             │ Passes
             ▼
┌─────────────────────────┐
│  LAYER 4: AUTOMATED     │  Unit and integration tests run
│  TESTS                  │  automatically on every code push.
│  (Continuous)           │  Focus: regressions, edge cases
│  Who: Infra + Dev team  │
└────────────┬────────────┘
             │ All layers pass
             ▼
       DELIVERED TO CLIENT
```

If any layer fails, the item goes back to the developer — it does not move forward.

### 6.3 QA Ownership

**Role Definition — QA Owner:**

| Responsibility | Description |
|---|---|
| Pre-delivery check | Reviews every deliverable before it goes to the client using the Definition of Done checklist |
| Bug gate | Anything not ready goes back to the developer — no exceptions |
| KPI logging | Logs pre-delivery bugs found in the daily KPI sheet |
| Smoke test lead | Runs the standard checklist after every deployment to staging |
| Escalation | If a deliverable has critical gaps close to deadline, escalates to PM immediately |

**Named QA Owners per Project:**

| Project | QA Owner | Backup QA Owner | Rotation (Every) |
|---|---|---|---|
| Create Project (BP) | To be nominated by team | To be nominated by team | 2–3 months |
| EMS | To be nominated by team | To be nominated by team | 2–3 months |
| FOCUST | To be nominated by team | To be nominated by team | 2–3 months |
| AI Phone Agent | To be nominated by team | To be nominated by team | 2–3 months |

> **Process:** Each team nominates their QA Owner this week. Criteria: not the person who wrote the feature being tested; understands the product well; has allocated time for QA duties.

**Rotation Policy:**
- QA Owner rotates every 2–3 months
- This builds QA competency across the whole team
- The outgoing QA Owner briefs the incoming one before handover

### 6.4 Definition of Done (DoD) Checklist

Before any feature or task can be marked complete, the following must all be true:

```
DEFINITION OF DONE — CHECKLIST
─────────────────────────────────────────────────────
□  Requirements confirmed in writing before work started
□  Developer has self-tested the feature
□  Code has been peer-reviewed
□  Feature works as expected in the staging environment
□  No obvious bugs or broken flows in staging
□  QA Owner has reviewed and signed off
□  Documentation updated if required (in /docs)
□  Client notified if delivery is imminent
─────────────────────────────────────────────────────
```

A Pull Request cannot be merged to staging unless the DoD checklist is confirmed.

### 6.5 Two-Environment Standard

| Environment | Purpose | Who Accesses It |
|---|---|---|
| **Development (Dev)** | Active feature development and testing | Developers only |
| **Staging** | Client acceptance testing; PM and QA validation | PM, QA Owner, Client (where applicable) |
| **Production** | Live, stable, client-facing system | Client and end users only |

**Rule:** No feature goes to Production without passing through Staging and receiving confirmation.

### 6.6 Release Governance

```
Developer finishes feature on Dev
         │
         ▼
QA Owner reviews on Staging
         │
    ┌────┴────┐
    │ Pass?   │
    └────┬────┘
  No ◄───┴───► Yes
  │                │
  Return to        PM confirms with client (if applicable)
  Developer        │
                   ▼
              Merge to Production
                   │
                   ▼
              Smoke test on Production
                   │
                   ▼
              EOD Report updated
```

---

## Section 7 — Communication Protocol

### 7.1 The 15-Minute Response Rule

Every client message received during working hours must receive a first response within **15 minutes**. This does not mean the issue must be solved in 15 minutes — it means the client must know their message has been received and is being handled.

### 7.2 The Three-Path Decision Tree

```
CLIENT MESSAGE RECEIVED
         │
         ▼
    ┌─────────────────────────────────────┐
    │ Can you answer this RIGHT NOW?      │
    └──────────────┬──────────────────────┘
           │               │
          YES              NO
           │               │
           ▼               ▼
    ┌──────────┐    ┌───────────────────────────────┐
    │  PATH A  │    │ Will it take 1–2 hours?        │
    │ Answer   │    └───────────────┬───────────────┘
    │ within   │            │               │
    │ 15 min   │           YES              NO
    └──────────┘            │               │
                            ▼               ▼
                     ┌──────────┐    ┌──────────────┐
                     │  PATH B  │    │   PATH C     │
                     │ Ack now  │    │ Ack now      │
                     │ Update   │    │ Update EOD   │
                     │ in 1 hr  │    │ (end of day) │
                     └──────────┘    └──────────────┘
```

### 7.3 Response Templates (Ready to Use)

**Path A — Immediate Response:**
Direct answer to the client's question, accurate and concise.

---

**Path B — Investigation Acknowledgment:**
> "Hi [Client Name], thank you for your message regarding [Topic]. I have flagged this with the team and we are currently reviewing the details. I will get back to you with a status update within the hour.
> Best regards, [Name]"

---

**Path C — Long-Term Acknowledgment:**
> "Hi [Client Name], thank you for reaching out about [Topic]. This requires a deeper review of [Area/Module]. We are looking into it and will provide a full status update in our end-of-day report, or sooner if resolved.
> Best regards, [Name]"

---

**1-Hour Update (for Path B):**
> "Hi [Client Name], a quick update: we have identified that the issue is related to [Area]. We are currently [testing/refining/investigating] the solution. I will confirm the final outcome in our daily report.
> Best regards, [Name]"

### 7.4 The 1-Hour Pulse Rule

If a Path B acknowledgment was sent, the Execution Owner must:
- Set a timer after sending the acknowledgment
- Provide a status update within 1 hour — even if the issue is not yet resolved
- Never let a client question go into the next day without a summary in the EOD report

### 7.5 Risk Escalation Process

```
Risk or delay identified by Developer/PM
         │
         ▼
Immediately notify PM (if not already the PM)
         │
         ▼
PM assesses impact on deadline
         │
         ▼
PM notifies Ambrose (Management Owner) at once
         │
         ▼
Ambrose decides:
  ├── Can the team handle it?  →  Team adjusts, client informed proactively
  └── Needs escalation?        →  Consult Prakhar/Nate same day
         │
         ▼
Client notified with:
  - What the risk is
  - Current impact on timeline
  - What the team is doing to address it
  - When the next update will come
```

> **Rule:** A delay communicated proactively is manageable. A delay communicated on the due date is a failure of the system.

### 7.6 What "Good Communication" Looks Like

| Scenario | Poor Practice | Good Practice |
|---|---|---|
| Requirements unclear | Start work, assume | Stop. Confirm in writing before starting |
| Task will be delayed | Say nothing until due date | Escalate as soon as the risk is recognized |
| Client asks a technical question | Wait until fully resolved | Acknowledge in 15 min, update in 1 hour |
| Bug found after delivery | Hope client doesn't notice | Notify client immediately with resolution plan |
| Meeting decision made | Forget by next day | Post decisions and next actions in channel same day |

---

## Section 8 — Reporting System

### 8.1 Daily Progress Report

The daily progress report serves **two audiences simultaneously** — the client and internal management. One message, consistent format, sent to the relevant channel at end of day.

**Template:**

```
Hello Team / Hello [Client Name],

Please find below the daily progress update for [Day, Date].

─────────────────────────────────────────────────────
1. PREVIOUS DAY PROGRESS
─────────────────────────────────────────────────────
- [Completed task or achievement]
- [Another completed item]
- [Any improvement or update made]

─────────────────────────────────────────────────────
2. PLANNED ACTIVITIES (NEXT)
─────────────────────────────────────────────────────
- [Next task / upcoming work]
- [Key priorities for the next period]

─────────────────────────────────────────────────────
3. RISKS / BLOCKERS (if any)
─────────────────────────────────────────────────────
[ ] None at this time
OR
- [Brief description of risk or blocker and current mitigation]

─────────────────────────────────────────────────────
4. SUPPORT NEEDED (if any)
─────────────────────────────────────────────────────
[ ] None
OR
- [Specify what input, approval, or assistance is required]

─────────────────────────────────────────────────────

Best regards,
[Name]
[Role / Team]
```

**Submission Rules:**
- Sent to the Daily Reports channel by **17:30 every working day**
- CC'd to the client where the project involves direct client communication
- PM is responsible for submission — QA Owner confirms accuracy of section 3

### 8.2 Weekly PDMO Summary

Produced by Ambrose after each Tuesday PDMO meeting. Shared in the team channel.

**Structure:**

```
WEEKLY PRODUCT MANAGEMENT UPDATE

Context
────────────────────────────────────────────
[2–3 sentence summary of what this week's
discussions covered and what it reflects.]

Project Health Overview
────────────────────────────────────────────
Project           │ Status
──────────────────┼──────────────
Create Project    │ 🟢 / 🟡 / 🔴
EMS               │ 🟢 / 🟡 / 🔴
FOCUST            │ 🟢 / 🟡 / 🔴
AI Phone Agent    │ 🟢 / 🟡 / 🔴

🟢 On Track   🟡 Watch / Minor Risks   🔴 Blocked

Project Summaries
────────────────────────────────────────────
[One short paragraph per project covering:
progress, current focus, risks, next steps]

Cross-Team Discussions & Key Decisions
────────────────────────────────────────────
[Any shared learnings, decisions, or
action items from the PDMO discussion]

Closing Note
────────────────────────────────────────────
[Brief encouragement and next steps for the team]
```

### 8.3 Client Reporting Guidelines

| Principle | Detail |
|---|---|
| **Frequency** | Daily (via EOD report) |
| **Tone** | Professional, honest, confident |
| **On delays** | Proactive — notify the moment risk is recognized |
| **On bugs** | Transparent — report immediately with resolution plan |
| **On progress** | Specific — avoid vague "in progress" without detail |
| **Language** | Clear and simple — avoid heavy technical jargon unless the client is technical |

---

## Section 9 — Meeting Structure & Schedule

### 9.1 Overview of the Meeting Ecosystem

```
DAILY                WEEKLY               PERIODIC
──────────────────────────────────────────────────────────
Company Standup      Product Meeting      TSS (Technical
(Mon–Fri, 09:00)     (per team, 15 min    Sharing Session)
                     after weekly         (Weekly, Friday)
Team Prep Meeting    team meeting)
(Mon–Fri, 09:10)                          Exploratory
                     PDMO Meeting         Cross-Team Testing
PM–Mgmt Sync         (Tuesday 14:00 EAT)  (During PDMO)
(09:20, as needed)
                     Weekly Tech Check
Peer Review          (per project)
(16:30 daily)

Management "Big 3"
(17:15 daily)
──────────────────────────────────────────────────────────
```

### 9.2 Company Standup

| Item | Detail |
|---|---|
| **Duration** | 6–10 minutes |
| **Frequency** | Daily, Monday to Friday |
| **Purpose** | Company-wide alignment on daily priorities |
| **Format** | Each person: What did I do? What will I do today? Any blockers? |
| **Rule** | No problem-solving in the standup — flag and address separately |

### 9.3 Team-Level Product Meetings (15 Minutes)

These sessions happen immediately after each team's regular weekly meeting. They are the foundation of the product management rhythm.

**Purpose:**
- Align on product priorities for the week
- Complete the weekly product checklist
- Surface blockers, bottlenecks, and missed requirements early

**Attendees:**
- All team members (mandatory)
- Project Manager (leads)
- Product Managers from other teams (optional — for cross-team learning)

**Confirmed Schedule:**

| Team | Meeting Day | Time |
|---|---|---|
| SNS | Monday | After 14:00 team meeting |
| AI Phone Agent | Tuesday | After 10:30 team meeting |
| Create Project | Wednesday | After 12:00 team meeting |
| EMS | Thursday | After 11:00 team meeting |
| FOCUST | Friday | After 10:00 team meeting |

> **Early validation:** The Create Project team's pilot session identified workflow bottlenecks and missed requirements, which were assigned and actioned immediately — directly demonstrating the value of this format.

### 9.4 Weekly PDMO Meeting (All Product Managers)

| Item | Detail |
|---|---|
| **Title** | Weekly PDMO Product Managers Sync |
| **Day & Time** | Tuesday at 14:00 EAT |
| **Duration** | 30–45 minutes |
| **Attendees** | All Product Managers + Ambrose |
| **Advisors** | Prakhar and/or Nate (as available) |

**Agenda:**

1. Welcome and purpose of the meeting
2. Updates from team product meetings
3. Review of templates and weekly checklist
4. Cross-team dependencies and key issues
5. Questions, actions, and next steps

### 9.5 Technical Sharing Sessions (TSS)

| Item | Detail |
|---|---|
| **Frequency** | Weekly (Friday) |
| **Duration** | 30 minutes |
| **Purpose** | Knowledge sharing, skill development, cross-team learning |
| **Format** | One team presents a technical topic; mandatory Q&A from other teams |
| **Output** | Summary documented in Aibos Atlas after the session |
| **Connection** | TSS content feeds into external technical blogs (Medium) |

**Rules for TSS:**
- Presenters prepare adequately to fit within 30 minutes
- Every attendee from other teams must ask at least one relevant question
- Key learning is documented within 24 hours of the session

### 9.6 Full Weekly Meeting Reference

| Day | Time | Meeting | Led By | Duration |
|---|---|---|---|---|
| Monday | 09:00 | Company Standup | Rotating | 10 min |
| Monday | After 14:00 | SNS Product Meeting | SNS PM | 15 min |
| Tuesday | 09:00 | Company Standup | Rotating | 10 min |
| Tuesday | After 10:30 | AI Phone Agent Product Meeting | Kevin (PM) | 15 min |
| Tuesday | 14:00 | PDMO — All PMs Sync | Ambrose | 30–45 min |
| Wednesday | 09:00 | Company Standup | Rotating | 10 min |
| Wednesday | After 12:00 | Create Project Product Meeting | Ambrose (PM) | 15 min |
| Thursday | 09:00 | Company Standup | Rotating | 10 min |
| Thursday | After 11:00 | EMS Product Meeting | EMS PM | 15 min |
| Friday | 09:00 | Company Standup | Rotating | 10 min |
| Friday | After 10:00 | FOCUST Product Meeting | FOCUST PM | 15 min |
| Friday | TBC | Technical Sharing Session | Assigned team | 30 min |

---

## Section 10 — Capacity Building & Continuity

### 10.1 The Problem This Solves

When a key person is unavailable, projects should not stall. When a team member leaves, knowledge should not leave with them. This section establishes the systems that make AIBOS Uganda resilient.

### 10.2 The Shadow / Backup System

For every project, there is a **Primary** lead and a **Shadow**. The Shadow is not a passive observer — they are an active participant who stays informed and is ready to take over at any point.

| Project | Primary Lead | Shadow / Backup | Shadow Responsibilities |
|---|---|---|---|
| Create Project | To be confirmed | To be confirmed | Attends prep meetings, CC'd on client comms, aware of all blockers |
| EMS | Martin / Andrew | To be confirmed | Same as above |
| FOCUST | FOCUST PM | To be confirmed | Same as above |
| AI Phone Agent | Kevin | To be confirmed | Same as above |

**Shadow Rules:**
- Shadow attends the team's product meeting every week
- Shadow is CC'd on all significant client communication
- If Primary is unavailable, Shadow steps in immediately with no ramp-up delay
- Shadow must be able to give a 5-minute status of the project at any time

### 10.3 Delegation Framework

Managers should move from doing to overseeing:

```
TODAY (Person-Dependent)          TARGET (System-Dependent)
──────────────────────────────────────────────────────────────
Manager writes every report       PM team rotates report writing
Manager monitors every project    KPI dashboard monitors projects
Manager answers every question    Response protocol handles it
Manager catches every bug         QA system catches bugs
Manager holds all knowledge       Documentation holds knowledge
──────────────────────────────────────────────────────────────
```

**Rotational Reporting:**
- Daily reports are not always written by the same person
- PMs rotate the reporting duty among team members
- This ensures every team member understands project status and can communicate it clearly

**Manager's New Role Checklist:**

| Old Activity | New Activity |
|---|---|
| Writing reports | Reviewing reports for quality |
| Answering every client question | Ensuring the protocol is followed |
| Catching bugs personally | Verifying the QA layer caught them |
| Knowing every detail | Knowing where the details are documented |

### 10.4 Technical Sharing Sessions as Capacity Engine

TSS sessions should actively build team capacity, not just share information passively.

**Active TSS Format:**

| Phase | Duration | Description |
|---|---|---|
| Presentation | 20 min | Team presents a technical topic, decision, or implementation |
| Q&A | 8 min | Other teams ask questions — minimum 1 question per attendee |
| Documentation | 2 min | Key points noted for Aibos Atlas entry within 24 hours |

**Cross-pollination rule:** The Shadow for a project should lead the Q&A for that project's TSS presentation — they have the most to learn and the most responsibility to stay current.

### 10.5 The SOP Library (Standard Operating Procedures)

**Rule:** If a task is done more than twice, it must have a written "How-To" guide.

SOPs are stored in Aibos Atlas under the relevant project category.

**Minimum SOP for any recurring task:**

```
SOP: [Task Name]
─────────────────────────
Purpose: What this task achieves
When to use: Trigger or frequency
Steps:
  1. ...
  2. ...
  3. ...
Owned by: [Role]
Last updated: [Date]
─────────────────────────
```

---

## Section 11 — Documentation & Knowledge Management

### 11.1 Philosophy

> **If it is not documented, it does not exist as a standard.**
> **If it is documented, it is assumed to be intentional.**

Documentation is not a chore — it is the mechanism by which individual knowledge becomes organizational knowledge. The DRY principle applies here too: document once, reference everywhere.

### 11.2 C2-PdMO Templates

The C2-PdMO (Product Design & Management Office) framework provides the standard document lifecycle for all projects.

**Document Lifecycle:**

```
Step 1: Define product vision        →  product.md
Step 2: Capture requirements         →  requirement-list
Step 3: Map functions                →  function-list
Step 4: Design architecture          →  architecture, tech, infrastructure, ADRs
Step 5: Track execution              →  weekly-tech-check
```

**Approval Gates:**

| Gate | Name | Required Documents |
|---|---|---|
| **G1** | Scope Lock | product doc, requirement-list, function-list |
| **G2** | Design Gate | architecture, tech stack, infrastructure, ADRs |
| **G3** | Release Gate | All tests pass, design-gate-checklist complete |

> **Rule: No code until G2 is passed.**

**Template Map:**

| Phase | Document | Purpose |
|---|---|---|
| Planning | product.md | Vision, goals, users, success metrics |
| Planning | requirement-list | What users need and why |
| Planning | function-list | What the system does |
| Design | architecture.md | How the system is structured |
| Design | tech.md | Approved technology stack |
| Design | infrastructure.md | Cloud resources and configuration |
| Design | adrs/ | Architecture Decision Records |
| Execution | weekly-tech-check.md | Health status and blockers |
| Execution | design-gate-checklist.md | Approval checkpoints |

**Reference:** [C2-PdMO Sample Meta on GitHub](https://github.com/aibos-dev/matrix-reorganization/tree/docs/c2-pdmo/02_Resources/sample-meta/docs/c2-pdmo)

### 11.3 Repository Documentation Standard

Every project repository must maintain a `/docs` folder with the following structure:

```
/docs
├── c2-pdmo/
│   ├── 1-planning/
│   ├── 2-design/
│   └── 3-execution/
│       └── YYYY-MM-DD-weekly.md
└── README.md
```

**ADR (Architecture Decision Record) Process:**

```
New architectural question arises
         │
         ▼
Create ADR (Proposed) — document the options and rationale
         │
         ▼
Review with team and Prakhar (if needed)
         │
    ┌────┴────┐
    │Accepted?│
    └────┬────┘
  No ◄───┴───► Yes
  │                │
  Mark rejected    Update architecture.md
  (keep for        Mark ADR as Accepted
  history)         Supersede any prior ADR
```

**Rules:**
- Every major architecture change starts as an ADR
- `architecture.md` always reflects the current accepted state
- Superseded ADRs are kept for historical reference

### 11.4 Aibos Atlas — Internal Knowledge Platform

**What it is:** A web-based internal knowledge system (built with Next.js) that serves as the single structured source of truth for organizational standards, reference architectures, playbooks, and operational guidelines.

**What it is not:** A replacement for GitHub or Google Drive. It fills the gap between code (GitHub) and files (Drive) by providing structured, searchable, project-organized institutional knowledge.

```
GitHub   →  Stores code and version history
Drive    →  Stores files and documents
Atlas    →  Structures institutional knowledge
```

**Content Domains:**

| Domain | What it Contains |
|---|---|
| Architecture | System design principles, deployment models, reference architectures |
| Product | Discovery playbooks, prioritization frameworks, release standards |
| Engineering | Coding standards, branching strategy, quality gates |
| Infrastructure | Cloud strategy, environment guidelines, security baselines |
| Operations | Incident management, escalation models, SLA definitions |
| Governance | Decision principles, review cadence, change management |

**Governance Model:**

- Each domain has an assigned owner (not a committee)
- Updates prioritize clarity over process
- Undocumented practices are not considered standards
- Product team is the primary custodian of Atlas

**Prototype:** [atlas-app-tbgo.vercel.app](https://atlas-app-tbgo.vercel.app)

**Roadmap:** Prototype → Internal deployment on AIBOS subdomain → Integration with weekly reporting

### 11.5 External Knowledge Sharing

As internal documentation matures, AIBOS Uganda will begin publishing external technical content.

| Channel | Purpose | Quality Standard |
|---|---|---|
| Medium (initial) | Technical blogs from TSS content | Solves a real problem; not generic AI-generated content |
| AIBOS Blog (future) | Company-owned technical publishing | Curated, quality-reviewed |

**Connection to TSS:** A TSS session can motivate a blog post, or a blog post can be presented in TSS. Both reinforce learning and external visibility.

**Ownership:** Product team initiates and manages quality control. Engineering teams are the authors.

---

## Section 12 — Reward & Motivation System

### 12.1 Philosophy

> **Systems sustain behavior. Recognition energizes it.**

At AIBOS Uganda's current stage, the most powerful rewards are **recognition and growth opportunity**, not just monetary incentives. The reward system should feel like *"this person made the team stronger"* — not a competition.

Recognition must be:
- Specific (tied to a real action or KPI outcome)
- Genuine (not generic praise)
- Consistent (not occasional)
- Framed around system contribution (not individual heroics)

### 12.2 Tier 1 — Weekly Recognition (Zero Cost)

Every Friday PDMO meeting includes a **"Team Highlight"** — one specific shoutout for a team or individual that exemplified the SLA/KPI standards that week.

This is posted in the team channel after the meeting.

**Examples of strong framing:**
- *"This week the FOCUST team reported a delay risk on Tuesday — three days before the deadline — giving us time to adjust. That is exactly the culture we are building."*
- *"AI Phone Agent had zero client-reported bugs this week. The QA layer worked exactly as designed."*

### 12.3 Tier 2 — Monthly KPI-Linked Awards

At the end of each month, review the KPI dashboard and recognize:

| Award | Criteria | Recognition |
|---|---|---|
| **Best Response Rate** | Fewest 15-min response violations | Shoutout + noted in monthly summary to Japan |
| **Cleanest Delivery** | Lowest post-delivery bugs reported by client | Shoutout + featured in PDMO summary |
| **Best QA Catch** | Most pre-delivery bugs caught internally | Shoutout — framed as "protected the team" |
| **Proactive Communicator** | Most delay risks escalated early | Shoutout — framed as "showed leadership" |
| **Documentation Champion** | Best/most consistent documentation update | Shoutout — connection to Aibos Atlas contribution |

### 12.4 Tier 3 — Quarterly Growth Reward

The top performing team member per quarter receives a **TSS Lead Slot** — they choose a topic of their interest and present it to the whole company.

This is a growth opportunity, not just a trophy:
- Builds the individual's profile internally
- Develops their communication and technical articulation skills
- Connects to the external blog initiative — their TSS becomes their first published blog post

**If budget allows:** A small monetary acknowledgment or team experience (team lunch, etc.) to accompany the TSS slot.

### 12.5 How to Frame Recognition

| Avoid | Use Instead |
|---|---|
| "You worked very hard" | "You protected the team by escalating early" |
| "Good job" | "Your QA catch prevented a client issue this week" |
| "You're the best developer" | "Your documentation means the next person can pick this up easily" |

The goal is to make excellence feel systemic and replicable, not exceptional and individual.

---

## Section 13 — MVP to Production Framework

### 13.1 The Recurring Challenge

Across multiple AIBOS Uganda projects, the same pattern has emerged: an MVP is built quickly to demonstrate a concept, and almost immediately the client expects it to function as a production-ready system. This has caused:

- Scope creep without proper planning
- Quality gaps because MVP code was not designed for production
- Team stress from rapid, unstructured transitions
- Feature additions without client confirmation (e.g., dark mode, extra features)

### 13.2 Stage Definitions

| Stage | Definition | Quality Expectation | Client Visibility |
|---|---|---|---|
| **MVP** | Built to validate feasibility or demonstrate a concept | May include shortcuts; not production-grade | Internal / invited preview only |
| **Demo** | Presentation-focused; optimized for clarity over completeness | Not assumed production-bound | Stakeholder preview on staging |
| **Beta** | Feature-complete but still being validated and stabilized | Near-production quality | Client tests on staging |
| **Production** | Stable, tested, and deployed for real users | Meets all QA gates | Live — client and end users |

### 13.3 Transition Guidelines

Before any stage transition, the following must be confirmed:

```
MVP → Demo
─────────────────────────────────────────────────
□  Core concept validated internally
□  No unconfirmed extra features added
□  Scope explicitly agreed with client

Demo → Beta
─────────────────────────────────────────────────
□  Requirements fully documented
□  Architecture reviewed (G2 gate passed)
□  Client aware this is still a validation stage

Beta → Production
─────────────────────────────────────────────────
□  All QA layers passed
□  Staging environment stable and client-tested
□  Client has confirmed readiness
□  Release governance completed
□  Production smoke test passed
```

### 13.4 Environment Flow

```
DEVELOPER
    │
    ▼
DEV environment
(feature built and developer-tested)
    │
    ▼
STAGING environment
(QA Owner reviews; client validates specific features)
    │
Client confirms
    ▼
PRODUCTION environment
(Feature released; monitoring active)
    │
    ▼
EOD report updated
```

### 13.5 Client Confirmation for Extra Features

> **Before adding any feature beyond the original scope, the PM must confirm with the client:**
> *"We are planning to add [Feature X]. Is this something you would like included?"*

This applies even when the feature seems helpful or proactive. A feature built without confirmation is a feature the client may not want to pay for.

### 13.6 Project Intake Process

Every new client project or major scope change must pass through the Product team before implementation begins.

```
Client submits new project / request
         │
         ▼
Product team receives and reviews
(Ambrose + relevant PM)
         │
         ▼
Product team assesses:
  - What is the scope?
  - What phase does it start at? (MVP/Beta/Production)
  - What team / resources are needed?
  - What is the delivery timeline?
         │
         ▼
Product team briefs the implementation team
         │
         ▼
G1 gate: Requirements documented
         │
         ▼
Implementation begins
```

---

## Section 14 — Implementation Roadmap

### 14.1 Overview

```
FEB 23        FEB 27        MAR 16          APR 1–30        MAY
────────────────────────────────────────────────────────────────────
Technical     Follow-up     TRIAL           PROVING         STRATEGY
Leaders       Meeting:      OPERATION       PERIOD
Meeting       Ambrose       BEGINS
              presents
              March Plan
────────────────────────────────────────────────────────────────────
```

### 14.2 Phase 1 — Foundation (Feb 23 – Mar 15)

**Goal:** Prepare the system. Build awareness. Assign ownership.

| Action | Owner | Target Date |
|---|---|---|
| Confirm Ambrose as Management Owner | Prakhar / Nate | Feb 23 |
| Share and review this framework document with Martin and Joseph | Ambrose | Feb 27 |
| Nominate QA Owners for each project | Each team | Feb 28 |
| Set up KPI tracking sheet (Google Sheets) | Ambrose | Mar 1 |
| Confirm shadow assignments per project | Ambrose + PMs | Mar 7 |
| Brief full team on daily pulse and SLA expectations | Ambrose + PMs | Mar 10–14 |
| Set up Aibos Atlas initial structure | Product team | Mar 14 |

### 14.3 Phase 2 — Trial Operation (Mar 16 – Mar 31)

**Goal:** Run the system. Identify friction. Adjust.

| What Goes Live | Notes |
|---|---|
| Daily Pulse (standup → prep → sync → peer review → EOD report) | Full cadence from day one |
| KPI daily logging begins | Each PM fills their row every evening |
| 15-min response protocol | All teams begin tracking |
| QA Owner role activated | DoD checklist used for every delivery |
| Weekly PDMO meeting running | Tuesday 14:00 EAT |
| Team product meetings running | Per confirmed schedule |

**Review points:** Ambrose reviews what is working and what feels "clunky" — adjustments made before April.

### 14.4 Phase 3 — Proving Period (Apr 1 – Apr 30)

**Goal:** Confirm adoption. Measure outcomes. Build confidence.

| Metric | Target |
|---|---|
| 15-min response violations | Trending toward zero |
| Delay risks escalated proactively | 80%+ of the time |
| Post-delivery bugs reported by client | Significant reduction from baseline |
| KPI sheet filled consistently | 90%+ completion rate |
| Team able to operate without Ambrose present for a day | Yes |

At the end of April, a review meeting with Prakhar and Nate confirms whether the system is functioning and what the next phase looks like.

### 14.5 Phase 4 — AI Integration Planning (May)

**Goal:** Once the operational foundation is stable, introduce AI tools to accelerate.

**Areas to explore:**
- Using Claude Code for automated test generation
- AI-assisted code review to supplement the QA layer
- Automated KPI reporting from existing data sources
- AI-assisted documentation drafting for Aibos Atlas

> **Important:** AI tools are introduced to accelerate a working system — not to fix a broken one. The April proving period must confirm system stability before this phase begins.

---

## Appendices

---

### Appendix A — Daily Report Template

```
Hello Team / Hello [Client Name],

Please find below the daily progress update for [Day, Date].

1. PREVIOUS DAY PROGRESS
- [Item 1]
- [Item 2]

2. PLANNED ACTIVITIES (NEXT)
- [Item 1]
- [Item 2]

3. RISKS / BLOCKERS (if any)
[ ] None at this time
OR: [Description and mitigation]

4. SUPPORT NEEDED (if any)
[ ] None
OR: [What is needed, from whom, by when]

Best regards,
[Name] | [Role / Team]
```

---

### Appendix B — 15-Minute Response Templates

**Path B — Investigation Acknowledgment:**
> "Hi [Client Name], thank you for your message regarding [Topic]. I have flagged this with the team and we are currently reviewing the details. I will get back to you with a status update within the hour. Best regards, [Name]"

**Path C — Long-Term Acknowledgment:**
> "Hi [Client Name], thank you for reaching out about [Topic]. This requires a deeper review of [Area]. We are looking into it and will provide a full update in our end-of-day report, or sooner if resolved. Best regards, [Name]"

**1-Hour Update:**
> "Hi [Client Name], a quick update: we have identified the issue is related to [Area]. We are currently [testing/investigating/refining] the solution. I will confirm the final outcome in our daily report. Best regards, [Name]"

---

### Appendix C — Definition of Done Checklist

```
DEFINITION OF DONE
──────────────────────────────────────────────
□  Requirements confirmed in writing before work started
□  Developer has self-tested the feature
□  Code has been peer-reviewed
□  Feature works correctly on staging
□  No obvious bugs or broken flows in staging
□  QA Owner has reviewed and signed off
□  Documentation updated if required
□  Client notified if delivery is imminent
──────────────────────────────────────────────
QA Owner sign-off: ___________________
Date: ___________________
```

---

### Appendix D — KPI Dashboard Template

| KPI | Mon | Tue | Wed | Thu | Fri | Weekly Total | Target |
|---|---|---|---|---|---|---|---|
| 15-min response violations | | | | | | | 0 |
| Delay risks escalated proactively | | | | | | | 100% |
| Pre-delivery bugs found in QA | | | | | | | Log trend |
| Post-delivery bugs (client reported) | | | | | | | 0 |
| On-time delivery | | | | | | | 100% |

---

### Appendix E — Weekly PDMO Agenda Template

```
WEEKLY PDMO PRODUCT MANAGERS SYNC
Tuesday | 14:00 EAT

1. Welcome and purpose of the meeting
2. Updates from team product meetings
3. Review of templates and weekly checklist
4. Cross-team dependencies and key issues
5. Questions, actions, and next steps
```

---

### Appendix F — Meeting Schedule Reference

| Day | Meeting | Led By | Duration |
|---|---|---|---|
| Mon | Company Standup | Rotating | 10 min |
| Mon | SNS Product Meeting | SNS PM | 15 min (after 14:00) |
| Tue | Company Standup | Rotating | 10 min |
| Tue | AI Phone Agent Product Meeting | Kevin (PM) | 15 min (after 10:30) |
| Tue | PDMO All-PMs Sync | Ambrose | 30–45 min (14:00) |
| Wed | Company Standup | Rotating | 10 min |
| Wed | Create Project Product Meeting | Ambrose | 15 min (after 12:00) |
| Thu | Company Standup | Rotating | 10 min |
| Thu | EMS Product Meeting | EMS PM | 15 min (after 11:00) |
| Fri | Company Standup | Rotating | 10 min |
| Fri | FOCUST Product Meeting | FOCUST PM | 15 min (after 10:00) |
| Fri | Technical Sharing Session | Assigned team | 30 min |

---

### Appendix G — C2-PdMO Document Reference Map

| Charter Requirement | Template Location | Status |
|---|---|---|
| Architecture Governance | 2-design/architecture.md, tech.md, adrs/ | Covered |
| Traceability (REQ→FUNC→COMP) | Throughout planning and design phases | Covered |
| Feasibility & Quality Audit | 3-execution/design-gate-checklist.md | Covered |
| Weekly Architecture Review | 3-execution/weekly-tech-check.md | Covered |
| Design Gate (Approval) | 3-execution/design-gate-checklist.md | Covered |
| Weekly Tech Check Format | 3-execution/weekly-tech-check.md | Covered |
| Design Approval Request | 1-planning/requirement-list, function-list | Covered |

---

*Document Owner: Ambrose Alanda — Product & Management Office, AIBOS Uganda*
*Version: 1.0*
*Last Updated: February 2026*
*For questions or updates: B1 Channel*
