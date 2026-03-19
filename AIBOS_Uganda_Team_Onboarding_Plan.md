---
title: "AIBOS Uganda: Team Onboarding Plan"
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
      page-break-after: avoid;
    }
    h4 {
      font-size: 9.5pt; font-weight: 700; color: #3b5bdb;
      text-transform: uppercase; letter-spacing: 0.07em;
      margin-top: 20px; margin-bottom: 8px;
    }
    p { margin-bottom: 12px; orphans: 3; widows: 3; }
    ul, ol { margin: 8px 0 14px 24px; }
    li { margin-bottom: 6px; }
    blockquote {
      background: #f0f4ff;
      border-left: 4px solid #3b5bdb;
      border-top: 1px solid #c5cbf9;
      border-right: 1px solid #c5cbf9;
      border-bottom: 1px solid #c5cbf9;
      padding: 12px 18px; margin: 18px 0; color: #1a1f36;
    }
    blockquote p { margin: 0; font-style: normal; }
    blockquote strong { color: #3b5bdb; }
    .warning {
      background: #fff8e1; border-left: 4px solid #f59f00;
      border-top: 1px solid #ffe066; border-right: 1px solid #ffe066;
      border-bottom: 1px solid #ffe066;
      padding: 12px 18px; margin: 18px 0; color: #1a1f36;
    }
    .success {
      background: #ebfbee; border-left: 4px solid #2f9e44;
      border-top: 1px solid #8ce99a; border-right: 1px solid #8ce99a;
      border-bottom: 1px solid #8ce99a;
      padding: 12px 18px; margin: 18px 0; color: #1a1f36;
    }
    .complete {
      display: inline-block; background: #2f9e44; color: #ffffff;
      font-size: 8pt; font-weight: 700; letter-spacing: 0.08em;
      text-transform: uppercase; padding: 2px 10px;
      border-radius: 3px; margin-left: 10px; vertical-align: middle;
    }
    pre {
      background: #1e2030; color: #c0caf5;
      padding: 16px 20px; margin: 16px 0;
      font-family: 'JetBrains Mono', 'Courier New', monospace;
      font-size: 8.5pt; line-height: 1.6; page-break-inside: avoid;
      border: 1px solid #2d3561;
    }
    pre code { background: transparent; color: #c0caf5; padding: 0; border: none; }
    code {
      font-family: 'JetBrains Mono', 'Courier New', monospace;
      font-size: 8.5pt; background: #eef0fb; color: #364fc7;
      padding: 2px 6px; border: 1px solid #c5cbf9;
    }
    table {
      width: 100%; border-collapse: collapse; margin: 18px 0;
      font-size: 9.5pt; page-break-inside: avoid; border: 1px solid #c8cfe8;
    }
    thead tr { background: #1a1f36; color: #ffffff; }
    thead th {
      padding: 10px 14px; text-align: left; font-weight: 600;
      font-size: 9pt; letter-spacing: 0.04em; border-right: 1px solid #2d3561;
    }
    thead th:last-child { border-right: none; }
    tbody tr { border-bottom: 1px solid #c8cfe8; }
    tbody tr:nth-child(even) { background: #f5f7fc; }
    tbody tr:last-child { border-bottom: none; }
    td { padding: 9px 14px; vertical-align: top; border-right: 1px solid #e2e6f0; }
    td:last-child { border-right: none; }
    hr { border: none; border-top: 2px solid #c8cfe8; margin: 40px 0; }
    strong { font-weight: 600; }
    .mermaid { margin: 28px 0; text-align: center; }
    .mermaid svg { max-width: 100%; height: auto; }
    header#title-block-header { display: none; }
  </style>
  <script src="https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.min.js"></script>
  <script>
    document.addEventListener('DOMContentLoaded', function () {
      mermaid.initialize({
        startOnLoad: true, theme: 'base',
        themeVariables: {
          primaryColor: '#eef0fb', primaryTextColor: '#1a1f36',
          primaryBorderColor: '#3b5bdb', lineColor: '#3b5bdb',
          secondaryColor: '#f5f7fc', tertiaryColor: '#ffffff',
          edgeLabelBackground: '#ffffff', fontSize: '13px'
        }
      });
    });
  </script>
---

# AIBOS Uganda: Team Onboarding Plan

### A Complete Strategy for Introducing the Delivery Framework to Every Role

**Version 2.0 — March 2026**

> **Purpose:** This document defines how every member of the AIBOS Uganda team is introduced to the System-Driven Delivery Framework — from leadership to engineers. It covers who needs to know what, how to sequence the onboarding, which methods to use, and how to confirm it has worked.

---

## Section 1 — Who Needs to Be Onboarded

Each person's daily reality is a specific slice of the framework. Onboarding must be designed around that slice — not the whole document.

The team has six roles. QA Owner and Shadow are responsibilities carried by existing team members — they are not separate people.

<div class="mermaid">
flowchart TD
    A["AIBOS Uganda Team"]
    A --> B["Leadership\nNate · Prakhar\nDepth: Awareness"]
    A --> C["Management Owner\nAmbrose\nDepth: Full"]
    A --> D["Project Manager\nCommunication + Engineering Oversight\nDepth: Deep"]
    A --> E["Product Manager\nQuality + Technical Gates\nDepth: Deep"]
    A --> F["Engineers\nDepth: Focused"]
    F --> G["QA Owner\nResponsibility held by an Engineer\nDepth: Role-specific"]
    F --> H["Shadow\nResponsibility held by an Engineer\nDepth: Continuity"]
    A --> I["New Hires\nDepth: Guided"]
</div>

| Role | What They Need to Understand | Session | Depth |
|---|---|---|---|
| **Leadership** (Nate, Prakhar) | System overview, governance structure, how to read status | 30 min | Awareness |
| **Management Owner** (Ambrose) | Full framework — runs all sessions, monitors adoption | Self-study | Full |
| **Project Manager** | Communication: DWC rotation, Client EOD, risk escalation, Shadow CC — and engineering oversight: 70/30 model, KPI trend review, quality patterns | 75 min | Deep |
| **Product Manager** | Quality: QA Owner, staging check, Internal SitRep, DoD, rework rate — and technical gates: major PR definition, Layer 1 review, architecture rules, No Ticket No Code | 75 min | Deep |
| **Engineer** | Daily actions: DoD checklist, GitHub hygiene, No Ticket No Code, self-test | 30 min | Focused |
| **QA Owner** *(Engineer carrying this responsibility)* | QA process: smoke test, staging post, DoD sign-off, KPI bug log | 30 min | Role-specific |
| **Shadow** *(Engineer carrying this responsibility)* | Continuity: readiness, handover template, weekly meeting attendance | 20 min | Continuity |
| **New Hire** | Everything relevant to their role, guided by a mentor | Structured | Guided |

---

## Section 2 — Phase-wise vs All at Once

| | All at Once | Phase-wise (Recommended) |
|---|---|---|
| **Approach** | Everyone briefed in the same week | One role group onboarded at a time |
| **Speed** | Fast — framework operational immediately | Slower — some roles run ahead of others temporarily |
| **Cognitive load** | High — team absorbs too much at once | Manageable — each group focuses on their slice |
| **Friction** | Questions pile up before anyone is practised | Friction found and fixed before it scales |
| **Coaching quality** | Management Owner cannot coach everyone at once | Management Owner can focus on each group properly |
| **Risk** | Compliance without understanding | Temporary inconsistency across teams |

### Why Phase-wise

Start with the roles that operate the system first — Project Managers and Product Managers. Their daily actions generate the outputs that other roles depend on. Once they are running, the engineering layer follows.

> **The sequencing principle:** Do not brief engineers on the DoD checklist before their Product Manager knows how to enforce it. Do not brief QA Owners before their Product Manager has nominated them. Each phase depends on the one before it.

---

## Section 3 — Onboarding Methods

No single method works for every role. Use a primary method to get the knowledge across and a reinforcement method to make it stick.

| Method | What it is | Best for |
|---|---|---|
| **Facilitated walkthrough** | Management Owner leads a focused session through the relevant sections | Project Managers, Product Managers |
| **Role-specific 1-pager** | One page showing only what this role does daily — kept as a standing reference | Every team member — given at the start of each session |
| **Live practice sprint** | The group runs their responsibilities for one real cycle, observed by the Management Owner | Project + Product Managers after their initial sessions |
| **Peer shadowing** | A practised team member walks a new one through their role in real time | New hires; engineers who learn by doing |
| **Retrospective-embedded learning** | First 10 minutes of each Tuesday PDMO addresses one open question from the previous week | All team members — first four weeks after full rollout |
| **Written FAQ document** | A shared doc where every onboarding question is captured and answered | All team members — maintained from day one |
| **Video walkthrough** | A recorded session explaining a key section | Future new hires; anyone who misses a live session |
| **Checklist confirmation** | Each team member signs off that they understand their role-relevant sections | End of every onboarding session |

---

## Section 4 — The Full Onboarding Sequence

Nine phases. Each phase covers one role group. No time constraints are embedded — the pace is determined by readiness, not the calendar.

<div class="mermaid">
flowchart TD
    P0["Phase 0 — COMPLETE\nPREPARATION\nManagement Owner only\nPrepare materials · Select pilot team"]
    P1["Phase 1 — COMPLETE\nLEADERSHIP ALIGNMENT\nNate · Prakhar\n30 min · Awareness + sign-off"]
    P2["Phase 2\nPROJECT MANAGERS\nCommunication + Engineering Oversight\nDWC · Client EOD · 70/30 · KPI trends"]
    P3["Phase 3\nPRODUCT MANAGERS\nQuality + Technical Gates\nQA Owner · Staging · DoD · Major PR · Architecture"]
    P4["Phase 4\nPILOT LIVE RUN\nProject + Product Managers\nOne full cycle · Friction identified"]
    P5["Phase 5\nENGINEERS\nDaily actions\nDoD · GitHub hygiene · Self-test"]
    P6["Phase 6\nQA OWNERS + SHADOWS\nQA role · Continuity\nSmoke test · Handover template"]
    P7["Phase 7\nFULL SYSTEM ACTIVE\nAll roles running\nWeekly PDMO monitoring loop"]
    P8["Phase 8\nNEW HIRE PROCESS\nOngoing\nMentor assigned from day one"]

    P0 --> P1 --> P2 --> P3 --> P4 --> P5 --> P6 --> P7
    P7 --> P8

    style P0 fill:#ebfbee,stroke:#2f9e44,color:#1a1f36
    style P1 fill:#ebfbee,stroke:#2f9e44,color:#1a1f36
</div>

---

## Section 5 — Session Plans by Phase

### Phase 0 — Preparation <span class="complete">Complete</span>

**Owner:** Management Owner | **Method:** Self-study and document preparation

Before any session runs, confirm the following are ready:

- [ ] Full framework (v3) read and understood — able to answer questions on every section
- [ ] Role-specific 1-pagers prepared for all role groups (see Section 8)
- [ ] FAQ Google Doc created and linked in the team channel
- [ ] Pilot team identified — one full project team (Project Manager + Product Manager + 2 Engineers)
- [ ] Google Drive folder structure live — Operations/, Projects/, Teams/
- [ ] KPI Google Sheet structured per Section 4.3 of the framework

---

### Phase 1 — Leadership Session <span class="complete">Complete</span>

**Duration:** 30 minutes | **Method:** Facilitated walkthrough | **Audience:** Nate, Prakhar

**What to cover:**

- The transformation goal — from person-dependent to system-driven delivery
- The seven pillars and what each one governs
- How leadership stays informed: KPI dashboard (permanent view access), weekly PDMO summary (shared every Tuesday after the meeting)
- What leadership is being asked to do: awareness and sign-off only — no operational involvement
- Where to raise concerns: Nate for operations and communication; Prakhar for development process and architecture decisions

**Output:** Leadership is aware, supportive, and knows exactly where to find status at any time.

---

### Phase 2 — Project Manager Session

**Duration:** 75 minutes | **Method:** Facilitated walkthrough + role 1-pager + checklist confirmation

The Project Manager owns two distinct areas: client communication and engineering oversight. Both are covered in this session.

#### Part A — Client Communication

**Open with the problem:** When the whole team monitors the client channel, no one feels individually accountable — and constant monitoring breaks developer focus. One named person per week solves both problems.

**1. The Designated Weekly Communicator (DWC)**

- One person per project monitors the client channel each week
- Project Manager names the DWC every Monday morning in standup
- Role rotates weekly — QA Owner is excluded in weeks they hold that role
- Project Manager trains their DWC on the three response templates

**2. The Three Response Templates**

| Situation | Response |
|---|---|
| Can answer immediately | Direct, accurate answer |
| Needs up to 1 hour | "Hi [Client], thank you for your message about [topic]. We are reviewing this and will get back to you within the hour. — [Name]" |
| Needs until end of day | "Hi [Client], thank you for reaching out about [topic]. We are looking into this and will include a full update in our end-of-day report. — [Name]" |

**3. Client EOD Report**

- Project Manager's daily output — sent to the client channel by 17:30
- Plain language only: no GitHub issue numbers, no KPI scores, no internal jargon
- Three sections: progress today / next steps / risks or delays

**4. Risk Escalation**

- Any risk to a deadline is escalated immediately upon recognition — never on the due date
- Path: Engineer → Project Manager → Management Owner → Client

**5. Shadow and Client Communication**

- Shadow must be CC'd on all significant client communications
- Project Manager confirms this is in place and maintains it going forward

#### Part B — Engineering Oversight

**Open with the context:** As AI tools raise the baseline output of every engineer, the Project Manager's highest-value role becomes oversight — not code. The 70/30 model reflects this shift.

**6. The Oversight Shift**

- Target allocation: approximately 70% oversight and QA review / 30% coding
- This is a gradual transition — it does not happen in week one
- The shift begins to take effect in Phase 3 (Proving Period) of the main framework

**7. What the 70% Oversight Looks Like**

- Review QA Owner staging results and KPI logs each morning
- Identify patterns in pre-delivery bugs — initiate process fixes when patterns repeat
- Mentor engineers through technically difficult tasks
- Monitor staging environment health and escalate to Product Manager if needed

**8. Reading the KPI Dashboard**

- The dashboard shows trends, not blame
- When a metric is poor, ask: which process failed? — not: who failed?
- Project Manager brings patterns to the Tuesday PDMO — not individual incidents

**Session exit checklist:**

- [ ] DWC named for this week — all projects confirmed
- [ ] Three response templates accessible and understood
- [ ] Client EOD format confirmed
- [ ] Shadow CC rule in place
- [ ] 70/30 target understood — gradual transition confirmed
- [ ] KPI dashboard access confirmed

---

### Phase 3 — Product Manager Session

**Duration:** 75 minutes | **Method:** Facilitated walkthrough + role 1-pager + checklist confirmation

The Product Manager owns two distinct areas: product quality and technical gates. Both are covered in this session.

#### Part A — Product Quality

**Open with the problem:** When QA belongs to everyone, it belongs to no one. As AI tools raise code output volume, informal QA breaks down faster. A named, rotating QA Owner fixes this.

**1. QA Owner Nomination**

- Every project needs a named QA Owner — Product Manager nominates one today
- If no engineer is ready, the Product Manager holds the role temporarily
- QA Owner rotates every 2–3 months — outgoing briefs incoming before handover

**2. The Async Staging Check**

- QA Owner runs the smoke test checklist at 16:30 daily
- Posts a pass/fail result in the team channel by 16:45
- Engineers are only involved if their specific PR caused a failure
- No team meeting required — fully asynchronous

**3. Internal SitRep**

- Product Manager's daily output — sent to the internal Daily Reports channel by 17:30
- Contains: GitHub delivery status, KPI log, risks, blockers
- Never shared with the client — distinct from the Client EOD

**4. Definition of Done**

- Product Manager enforces the DoD checklist before anything goes to the client
- Key gates: GitHub Issue exists → requirements confirmed in writing → PR reviewed and approved → QA Owner signed off

**5. Rework Rate**

- The Product Manager's primary quality metric (C-2 PdMO mandate)
- Tracks the percentage of work corrected due to insufficient requirements or design errors
- Logged per Epic/Task completion and reviewed at every PDMO

#### Part B — Technical Gates

**Open with the context:** The Product Manager is also responsible for enforcing the technical gates that protect code quality before delivery. These are not optional checks — they are system mandates.

**6. Layer 1 PR Review**

- An AI code review tool handles all routine PRs automatically
- Product Manager ensures manual review happens for every PR that qualifies as "major"
- The AI tool reviews first; manual review follows

**7. Definition of a Major PR**

| Criterion | Example |
|---|---|
| New service or module | New API service, new authentication flow |
| Changes to authentication or security | Login logic, token handling, permissions |
| Database schema migration | Adding, altering, or removing tables |
| Cross-system integration | New third-party API, payment provider |
| 200 or more lines changed | Large refactors affecting multiple behaviours |
| New dependency added | Any new package or library |
| Breaking change to an existing API | Changes that break a live endpoint |

If in doubt, the engineer flags it for manual review.

**8. Architecture Gates**

- No technology outside the approved stack without a formal RFC and C-2 PdMO approval
- Architecture Decision Records (ADRs) document every major architectural choice
- No code is written until the Design Gate (G2) is passed

**9. No Ticket, No Code**

- Every PR must be linked to a GitHub Issue — no exceptions
- Product Manager enforces this rule and flags violations immediately
- Compliance is audited at the twice-weekly C-3 PMO check

**Session exit checklist:**

- [ ] QA Owner named for every project
- [ ] Async staging check process understood
- [ ] Internal SitRep format confirmed
- [ ] DoD checklist key gates memorised
- [ ] Rework rate tracking understood
- [ ] Major PR criteria understood and saved for reference
- [ ] AI code review tool confirmed and running on all repositories
- [ ] Architecture gate process understood
- [ ] No Ticket No Code enforcement confirmed

---

### Phase 4 — Pilot Live Run

**Duration:** One full work cycle | **Method:** Live practice sprint | **Audience:** Project + Product Managers

Before briefing the engineering layer, Project Managers and Product Managers run their full responsibilities for one real cycle. The Management Owner observes and coaches.

| Activity | Owner | When |
|---|---|---|
| DWC named and active | Project Manager | Monday morning |
| Client channel monitored | DWC | Throughout the day |
| Staging check posted | QA Owner (or Product Manager) | 16:45 daily |
| KPI sheet filled | Product Manager | 17:00 daily |
| Client EOD sent | Project Manager | 17:30 daily |
| Internal SitRep sent | Product Manager | 17:30 daily |
| PDMO review | Both | Tuesday 14:00 |

**Output:** Friction points are documented in the FAQ doc. One fix is applied before Phase 5 begins.

<div class="warning">

**Gate before Phase 5:** Both EOD reports are being sent consistently. The DWC rotation is running without prompting. A QA Owner is confirmed and posting on every project.

</div>

---

### Phase 5 — Engineer Session

**Duration:** 30 minutes | **Method:** Facilitated walkthrough + role 1-pager

Engineers need clarity on their daily actions — not the full framework. Keep the session tight.

**1. Before Writing Any Code**

- Does a GitHub Issue exist for this task? If not, create one before starting
- Is the issue assigned with a deadline? If not, confirm with the Product Manager

**2. Before Raising a PR**

- Self-test the feature in the development environment
- Run through the Definition of Done checklist — all items must be true
- Link the GitHub Issue in the PR description

**3. GitHub Issue Status — Keep It Current**

| Status | When to set it |
|---|---|
| `In Progress` | When you start work |
| `To be Reviewed` | When the PR is raised |
| `To Production` | When the QA Owner signs off |
| `Done` | When deployed and confirmed on production |

**4. Automated Tests**

- Write basic unit tests for your own code before raising a PR
- Playwright E2E setup is being introduced — you will be briefed when it is ready
- If an automated test fails in the pipeline, fix it before requesting review

**5. The Async Staging Check**

- You do not attend the 16:30 staging check
- If the QA Owner tags you in a FAIL post, respond and fix before EOD reports are sent

**Session exit checklist:**

- [ ] GitHub Issue before code confirmed
- [ ] DoD checklist location known
- [ ] GitHub Issue status fields understood
- [ ] Async staging check response understood

---

### Phase 6a — QA Owner Session

**Duration:** 30 minutes | **Method:** Facilitated walkthrough + practice run on staging

This session is for the engineer nominated as QA Owner on each project. Run separately from the general engineer session.

**1. The QA Owner's Daily Routine**

```
16:30  Open the staging environment
       Run the smoke test checklist item by item
16:45  Post result in the team channel:
         PASS: "[Project] staging clear. All checks passed."
         FAIL: "[Project] staging issue: [description]. @[engineer] please review."
17:00  Confirm status to the Product Manager
```

**2. The Smoke Test Checklist**

Walk through each item on the checklist (Section 6.4 of the framework) on a live staging environment. Practice running it end-to-end during the session — do not explain it in theory only.

**3. KPI Bug Logging**

- Every bug caught before the client sees it is logged in the KPI Google Sheet that same day
- This data is not punitive — it is the team's quality signal and is reviewed at PDMO

**4. Definition of Done Sign-Off**

- QA Owner signs the DoD checklist before any feature moves to Production
- If a feature is not ready, it goes back to the engineer — no exceptions and no deadline overrides
- Escalate to the Product Manager if a deadline conflict arises

**5. Rotation**

- Role rotates every 2–3 months
- Outgoing QA Owner briefs incoming QA Owner before the handover date
- A Backup QA Owner must always be named

**Session exit checklist:**

- [ ] Smoke test checklist practiced on a live staging environment
- [ ] Pass/fail post format confirmed
- [ ] KPI bug logging confirmed
- [ ] DoD sign-off process confirmed
- [ ] Backup QA Owner named

---

### Phase 6b — Shadow Briefing

**Duration:** 20 minutes | **Method:** Brief walkthrough + handover template review

**What the Shadow role means:**

The Shadow is not a passive backup. They are an active continuity partner — present enough that stepping in requires no ramp-up.

**Three standing responsibilities:**

1. Attend the weekly product meeting every week without exception
2. Be CC'd on all significant client communications (Project Manager ensures this)
3. Be able to give a 5-minute project status update at any time without preparation

**Handover template:**

The Shadow Handover Template is stored in Google Drive under Operations/Templates/. Walk through it in the session and confirm the Shadow knows when and how to use it.

**Session exit checklist:**

- [ ] Attendance at weekly product meeting confirmed going forward
- [ ] CC'd on client communications from this point
- [ ] Handover template reviewed and location bookmarked
- [ ] 5-minute project status tested in the session

---

## Section 6 — The Running Rhythm After Full Onboarding

Once all phases are complete, this is what the system looks like at full capacity.

<div class="mermaid">
sequenceDiagram
    participant PM as Project Manager
    participant PdM as Product Manager
    participant Eng as Engineer
    participant QA as QA Owner
    participant DWC as DWC

    Note over PM,DWC: Monday — DWC confirmed in standup
    PM->>DWC: Names this week's DWC
    DWC->>DWC: Monitors client channel all week

    Note over Eng,PdM: During the day
    Eng->>Eng: Creates GitHub Issue before coding
    Eng->>PdM: Raises PR linked to Issue
    PdM->>PdM: AI tool reviews routine PRs
    PdM->>PdM: Manual review for major PRs

    Note over PM: Project Manager reviews KPI trends and flags patterns
    PM->>PdM: Flags engineering quality patterns

    Note over QA,PdM: 16:30 — Async staging check
    QA->>QA: Runs smoke test checklist
    QA->>PdM: Posts pass/fail by 16:45

    Note over PdM,PM: 17:15 — Pre-EOD sync
    PdM->>PM: Shares any quality risks for EOD

    Note over PM,PdM: 17:30 — EOD Reports
    PM->>PM: Sends Client EOD to client channel
    PdM->>PdM: Sends Internal SitRep to team channel
</div>

### Weekly Pattern

| Day | Project Manager | Product Manager |
|---|---|---|
| **Monday** | Name DWC in standup; review last week's KPI trends | Confirm QA Owner active |
| **Tue–Thu** | Monitor DWC; handle risk escalations; flag engineering quality patterns | Review KPI entries; check staging results; co-review major PRs |
| **Tuesday 14:00** | PDMO: report response SLA + delivery status + quality patterns | PDMO: report bug rates + rework rate + technical gate compliance |
| **Friday** | Confirm week's delivery vs. plan; check team workload for coming week | Review pre-delivery bug log for patterns |

---

## Section 7 — Monitoring That Onboarding Has Worked

Onboarding is complete when the behaviours are happening without prompting — not when the sessions are done.

### Four-Week PDMO Check

For the first four weeks after all phases are complete, open every Tuesday PDMO with a brief review:

| Week | Check | What good looks like |
|---|---|---|
| **Week 1** | Is the DWC named every Monday? Is the staging check posted daily? | Both happen without a reminder |
| **Week 2** | Are both EOD reports being sent? Is the KPI sheet filled each day? | No empty rows; Client EOD is plain language |
| **Week 3** | Are Project Manager and Product Manager coordinating before 17:30? Are engineers creating Issues before coding? | No contradictions between EOD reports; no PRs without Issues |
| **Week 4** | Is the Project Manager reviewing trends rather than fixing bugs personally? Are QA Owners posting independently? | PM raises patterns at PDMO; QA posts are consistent |

<div class="success">

**The onboarding has worked when:**

- DWC is confirmed every Monday without a reminder
- Staging check posts appear in the channel by 16:45 every working day
- Both EOD reports are sent daily — the Client EOD is readable by a non-technical person
- GitHub Issues exist for every task in progress — no orphaned PRs
- Project Manager brings quality trends to PDMO, not individual bug fixes
- Shadows can give a 5-minute project update without preparation
- The Management Owner spends PDMO time on decisions, not re-explaining the framework

</div>

<div class="warning">

**Warning signs — raise at the next PDMO:**

- DWC rotation is forgotten and the Project Manager handles all communications personally
- Staging check posts are missing for two or more consecutive days
- Client EOD contains GitHub issue numbers or internal KPI data
- PRs are raised without linked Issues
- Project Manager is spending more than 70% of time on feature coding
- QA Owner post pattern breaks and no one escalates it

</div>

---

## Section 8 — Quick Reference Cards

One card per role. Each card shows daily actions and the key rules to remember.

### Project Manager

> **Owns: Client communication, DWC rotation, Client EOD, risk escalation, engineering oversight, KPI trend review**

**Daily actions:**

- Monday: Name this week's DWC in standup; review last week's KPI trends
- During the day: Trust the DWC — do not monitor client channels yourself; review KPI logs and staging results for patterns
- By 17:15: Check with Product Manager — any quality risks to include in the EOD?
- By 17:30: Send Client EOD to client channel — plain language, no internal data
- Immediately: Escalate any deadline risk the moment it is recognised

**Three rules:**

1. Only the DWC monitors the client channel — you assign, train, and rotate the role
2. The Client EOD is for the client — no GitHub numbers, no KPI scores, no internal jargon
3. Your job is to ensure the system catches problems — not to catch every problem yourself

---

### Product Manager

> **Owns: QA process, QA Owner, Internal SitRep, bug KPIs, rework rate, major PR review, architecture gates, No Ticket No Code**

**Daily actions:**

- Monday: Confirm QA Owner is active for the week
- By 16:45: QA Owner posts staging result — act immediately if FAIL
- By 17:00: Fill KPI sheet row — honest numbers, observation mode in Phase 2
- By 17:15: Inform Project Manager of any quality risks before EODs are written
- By 17:30: Send Internal SitRep to the Daily Reports channel

**Three rules:**

1. Nothing goes to the client without QA Owner sign-off on the DoD checklist
2. The Internal SitRep is for the team only — never share it with the client
3. No PR merged without review — AI tool for routine PRs, manual review for major PRs

---

### Engineer

> **Owns: Clean code delivery, GitHub hygiene, self-testing**

**Daily actions:**

- Before coding: Confirm a GitHub Issue exists — create one if it does not
- Before raising a PR: Self-test; check the DoD checklist; link the Issue in the PR
- Keep GitHub Issue status current at every stage
- If the QA Owner tags you in a FAIL post: fix the issue before EOD reports are sent

**Three rules:**

1. No ticket, no code — if there is no GitHub Issue, stop and create one first
2. Self-test before raising a PR — the QA Owner is the second check, not the first
3. Keep your GitHub Issue status current — stale issues cause confusion for everyone

---

### QA Owner *(Engineer carrying this responsibility)*

> **Owns: Async staging check, DoD sign-off, pre-delivery bug logging**

**Daily actions:**

- 16:30: Run the smoke test checklist on staging
- 16:45: Post pass/fail result in the team channel — silence is not a pass
- Log every pre-delivery bug in the KPI Google Sheet that same day
- Sign the DoD checklist before any feature moves to Production

**Three rules:**

1. Post the staging result every day — a PASS still needs to be posted
2. If a feature is not ready, it goes back to the engineer — no deadline overrides the checklist
3. Escalate to the Product Manager if a quality risk arises near a deadline — do not manage it silently

---

### Shadow *(Engineer carrying this responsibility)*

> **Owns: Continuity — ready to step in immediately, without ramp-up**

**Standing responsibilities:**

- Attend the weekly product meeting every week — no exceptions
- Be CC'd on all significant client communications
- Keep the Shadow Handover Template current in Google Drive
- Know the current project status well enough to brief anyone in five minutes

**One rule:** If the Primary is unavailable, step in immediately. There is no transition period — you have been present throughout.

---

## Section 9 — New Hire Onboarding

Every new team member follows this sequence regardless of when they join.

<div class="mermaid">
flowchart TD
    NH["New hire joins"]
    D1["Day 1\nShadow mentor assigned\nRole 1-pager received\nAdded to relevant channels"]
    D2["Days 1 to 3\nReads role-relevant sections\nGuided by the 1-pager\nQuestions go to mentor or FAQ doc"]
    D3["Day 3\n30-min conversation with Project Manager\nQuestions answered\nExpectations confirmed"]
    W1["Week 1\nObserves the Daily Pulse\nNo DWC or QA duties yet\nMentor explains what is happening and why"]
    W2["Week 2\nTakes on assigned role duties\nDWC and QA rotation with mentor support\nMentor confirms readiness before solo work"]
    W3["Week 3 onward\nOperating independently\nMentor available for questions\nProgress reviewed at next PDMO"]

    NH --> D1 --> D2 --> D3 --> W1 --> W2 --> W3
</div>

> **Rule:** No new team member starts client-facing work without completing this sequence. The Shadow mentor confirms readiness to the Project Manager before the new hire operates independently.

---

## Section 10 — Time Key

The sequence above has no embedded dates. Use this table as a planning guide — the gate condition determines when to move on, not the calendar.

| Phase | Suggested Duration | Gate Condition |
|---|---|---|
| Phase 0 — Preparation | 3–5 days | All materials ready; pilot team confirmed |
| Phase 1 — Leadership | 1 session | Leadership aware and supportive |
| Phase 2 — Project Managers | 1–2 days | DWC active; Client EOD being sent daily |
| Phase 3 — Product Managers | 1–2 days | QA Owner named; staging check running daily |
| Phase 4 — Pilot Live Run | 1–2 weeks | Both EOD reports consistent; friction documented and fixed |
| Phase 5 — Engineers | 1 day | All engineers creating Issues before code; DoD understood |
| Phase 6 — QA Owners + Shadows | 1 day | QA Owners posting daily; Shadows attending product meetings |
| Phase 7 — Full system active | Ongoing | Weekly PDMO monitoring loop running |
| Phase 8 — New hires | 2 weeks per person | Ongoing — applies to every new team member |

---

> **This document is a companion to the AIBOS Uganda System-Driven Delivery Framework (Version 3.0) and the Must-Do Action Plan. All role definitions, templates, checklists, and process details referenced here are defined in full in the main framework document.**
