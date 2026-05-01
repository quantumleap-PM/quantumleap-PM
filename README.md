<!-- Gautam Sah — GitHub Profile README -->
<!-- Drop this file into a repo named exactly: gsah (your GitHub username) -->

<div align="center">

# Gautam Sah

**Senior Product Manager · 10+ Years**

*FinTech · B2B SaaS · AI Platforms · EdTech · Travel-Tech*

Pune, India · Open to remote & relocation

[![Portfolio](https://img.shields.io/badge/Portfolio-Notion-black?style=flat-square&logo=notion)](https://www.notion.so/33ef664f2ddd81c39d00e97a3c38ce10)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-gsah-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/gsah)
[![Miro](https://img.shields.io/badge/Miro-Live_Diagrams-F7C922?style=flat-square&logo=miro&logoColor=000)](https://miro.com/app/board/uXjVGi8P18I=/)
[![Email](https://img.shields.io/badge/Email-gs.quantumleap@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:gs.quantumleap@gmail.com)

</div>

---

> **I build systems that change user behaviour — not just features that ship.**
>
> I've disagreed with VPs, blocked engineering decisions, and killed campaigns that had full stakeholder consensus — because the data said no. Every call is documented. Every failure has a post-mortem.

---

## ⚡ Impact at a Glance

| Metric | Value | Company |
|--------|-------|---------|
| KYC onboarding TAT | **72 hours → <1 hour (−98%)** | Lentra AI |
| Checkout CVR | **42% → 55% (+13pp)** | Brainvire |
| Trial activation | **+45%** | WhiteHat Jr |
| Annual ops cost saved | **$150,000** | Lentra AI |
| Monthly bookings managed | **1M+** | IndiGo Airlines |
| NPS improvement | **35 → 50+** | WhiteHat Jr |
| Features shipped | **250+ in 18 months** | Brainvire |
| Learners scaled | **200K+** | WhiteHat Jr |

---

## 🔬 Case Studies

### 01 · KYC Automation — Lentra AI (FinTech · 2022–23)

**Problem:** 72-hour onboarding TAT was blocking bank adoption. The real blocker wasn't technology — it was compliance fear.

**Riskiest assumption validated:** 6 compliance-officer interviews. 100% said the same thing: *"We're not afraid of AI — we're afraid of not being able to explain a decision to the RBI auditor."*

**What I built:**
- 3-tier configurable decisioning architecture (per-bank confidence thresholds)
- Aadhaar + DigiLocker auto-pull · Async CIBIL (no page freeze) · Human-in-loop for edge cases
- Full audit trail per application — RBI-compliant

**The hard decision:** Engineering wanted full automation. I blocked it. One bad batch during an RBI audit = contract loss for 4 banks. I held the line. We shipped the configurable architecture in 8 weeks instead.

**Results:** TAT 72hr → <1hr · 88% straight-through · $150K annual ops saved · Zero regulatory incidents

---

### 02 · Checkout Redesign — Brainvire (E-commerce · 2023–25)

**Problem:** 68% cart abandonment. Exit surveys: only 8% cited price. 60% of all drop-off was at the payment error screen.

**Riskiest assumption validated:** 40 session recordings + Mixpanel funnel. The error state — not the product, not the price — was the conversion killer.

**What I built:**
- Single-page checkout with persistent cart · Inline field-specific error copy · Payment state persistence
- Twilio SMS at 30-min with named-item copy (+18% CTR vs generic "your cart")
- 3 A/B variants in 30 days · Variant C shipped week 10

**The hard decision:** VP pushed for discount-at-abandonment in 4 consecutive reviews. I said no in all 4 — with the same revenue model, updated each time. Modelled LTV erosion vs $280K from checkout redesign. On review 4, he agreed.

**Results:** CVR 42% → 55% · Cart abandonment 68% → 51% · +12% abandoned transaction recovery

---

### 03 · Trial Activation — WhiteHat Jr (EdTech · 2020–22)

**Problem:** 18% trial-to-paid CVR. Badge gamification was failing at week 3.

**The insight (interview #47 of 150):** *"My son showed his game to his classmates on day 1. That's when I knew we'd keep paying."* Cohort data confirmed: 31% CVR with session-1 project vs 14% without.

**What I built:**
- Session 1 always ends with a deployable shareable game link (milestone moment guaranteed)
- AI teacher matching: 6-dimension model · Cold-start cohort priors · Feedback loop for model retraining
- "Share with friends" → public URL → external social proof

**The hard decision:** Killed badge gamification at week 6. The eng lead pushed back — week-1 DAU was up 24%. I sat with the week-3 cohort chart for 48 hours. The right call often feels like overreaction in the moment.

**Results:** Trial activation +45% · CVR 18% → 22% · NPS 35 → 50+ · Brazil +52% activation

---

## 💡 My Product POV

These aren't frameworks. They're positions I've taken, defended under pressure, and validated with data.

**1. The error state IS the product.**
Most conversion problems aren't price or feature gaps — they're broken recovery paths. Fix the error copy before you add a feature.

**2. Full automation is a liability, not a goal.**
One RBI audit failure ends 4 bank contracts. Configurable human-in-loop isn't a compromise — it's the architecture that scales.

**3. Gamification that doesn't leave the product doesn't work.**
Badges spiked engagement for 2 weeks. Shareable project links sustained it for 8+. External value outlasts in-app status.

**4. Social proof at the wrong moment destroys trust.**
A "live purchase count" banner at checkout reduced CVR by 2.1pp. Completion mindset ≠ discovery mindset. Context beats pattern.

**5. Validate the riskiest assumption before writing a PRD line.**
This has changed my direction on every case study in this portfolio.

---

## 🏗️ System Thinking

I don't just spec features — I design the systems they live inside.

At Lentra, the hardest part wasn't the AI model. It was designing a system a regulator could trust:

```
INPUT         → PROCESSING      → DECISION         → OUTPUT
──────────────────────────────────────────────────────────
Aadhaar +       OCR extraction    Per-bank tier 1    SMS approval
DigiLocker  →   Async CIBIL   →   auto-approve   →   Bank dashboard
3-field form    Confidence         Tier 2 refer        Disbursement
                scoring            Tier 3 manual        trigger
                                   (audit trail)
```

**Bottleneck I fixed:** Sync CIBIL caused 18-sec page freezes at 200+ concurrent sessions → 30% drop-off. Moved to async. Drop-off eliminated.

**What I optimised first:** Tier 1 auto-approve rate. Banks renew contracts when it's ≥85%. Everything else was secondary until that number was stable.

---

## 🧠 How I Think About a New Problem

*Example: UPI payment failures causing 15% checkout drop-off*

| Step | What I do |
|------|-----------|
| **Frame** | Not "why do UPI payments fail?" → Ask: "At what point does the user believe they've paid — but haven't — and why don't they retry?" |
| **Hypotheses** | H1: Generic error copy · H2: App timeout vs network failure looks identical · H3: Retry CTA buried · H4: Cart state lost on back nav |
| **Metrics** | Primary: UPI retry rate per error type · Guard: False retries (double-charge risk — non-negotiable) |
| **Trade-off** | Specific error copy = 2-week eng effort. Generic retry = 2 days. Test generic first. If retry rate lifts ≥15% in 7 days → ship. |
| **First experiment** | Deploy "Try again with UPI" CTA with 3-tap retry loop. A/B vs control. Cap at 10 days. |

---

## 🗓️ Career Timeline

```
2014 ──────── 2019 ──── 2020 ──────── 2022 ──── 2023 ─────── 2025
  │               │         │              │          │
IndiGo          Yatra    WhiteHat Jr    Lentra AI  Brainvire
Aviation     Travel-Tech   EdTech        FinTech   B2B SaaS
1M+ bkgs/mo  Rev/txn +22%  200K+ users  TAT −98%   CVR +13pp
APM → PM     Digital PM    PM           PM         PM
```

---

## 🛠️ Product Stack

```
Discovery & Research    Figma · Miro · Mixpanel · SQL · Hotjar
Prioritisation          RICE · WSJF · Opportunity Scoring
Delivery                Jira · Azure DevOps · Confluence
Technical               Postman · API contract review · async patterns
Analytics               Mixpanel · Google Analytics · Tableau · SQL
AI/ML fluency           Precision/recall · human-in-loop · retraining loops
CRM                     Salesforce · HubSpot
Certs                   CSPO · AWS Cloud Practitioner · Lean Six Sigma Green Belt
```

---

## 📊 Failed Experiments (the portfolio most PMs hide)

| Experiment | What failed | The pivot | The learning |
|------------|-------------|-----------|--------------|
| Social proof banner at checkout | −2.1pp CVR | Removed all comparative signals | Completion mindset ≠ discovery mindset |
| Sync CIBIL API | 18-sec freeze at load | Async background job | Always concurrency-test 3rd-party APIs |
| Badge gamification | Novelty faded week 3 | Shareable project outputs | External value outlasts in-app status |
| Interview bias (WhiteHat Jr) | First 46 interviews confirmed wrong hypothesis | Added emotional arc question to script | "Walk me through the moment you decided to…" |

---

## 🔗 Full Portfolio

| Resource | What's inside |
|----------|---------------|
| [📋 Notion Portfolio](https://www.notion.so/33ef664f2ddd81c39d00e97a3c38ce10) | 15 pages: case studies, storytelling, RICE, system thinking, metrics, social proof |
| [🟡 Miro Board](https://miro.com/app/board/uXjVGi8P18I=/) | 8 flowchart diagrams · 5 structured docs · Journey maps · Retrospectives |
| [🎨 Figma Wireframes](https://www.figma.com/design/SrBlGY8H0vyR0MtN8AgQQ5/) | Checkout before/after · KYC 6-screen flow · Cover |
| [💼 LinkedIn](https://linkedin.com/in/gsah) | Full experience, recommendations |

---

<div align="center">

**Open to Senior / Staff PM roles at high-scale B2B SaaS, FinTech, and AI-native companies.**

*gs.quantumleap@gmail.com · +91 78359 60940*

</div>
