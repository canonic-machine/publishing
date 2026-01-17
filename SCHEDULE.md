# PUBLISHING SCHEDULE

**Status:** ACTIVE
**Evidence Window:** v0.1 (2026-01-17)

---

## 1. Purpose

Define the dissemination schedule for CANONIC artifacts per PUBLISHING CANON.

This schedule is governed by:
- PUBLISHING Axiom 2 (Evidence anchoring)
- PUBLISHING Axiom 3 (Time-to-publication disclosure)
- PAPER Axiom 8 (Versioning discipline)

### Current State (v0.1)

| Metric | Value |
|--------|-------|
| IDFs | 136 |
| Atomic axioms | 86 (T/I/N decomposition) |
| Validators | 89 operational |
| Scopes passing | 55 |
| Episodes | 168+ |
| App Store | GitHub (discovered Episode 168+) |

See [/validators/CATALOGUE.md](/validators/CATALOGUE.md) for the VaaS product catalogue.
See [/companies/foundation/FOUNDATION.md](/companies/foundation/FOUNDATION.md) for the Foundation roadmap.

### Ouroboros Discovery (IDF-136)

During this evidence window, the system discovered its own distribution channel:

**GitHub IS the App Store.**

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│   WE BUILD: VaaS validators + GitHub Action                     │
│   GITHUB BUILDS: Everything else                                │
│                                                                 │
│   Distribution = GitHub Actions Marketplace                     │
│   Billing = GitHub Marketplace / Stripe                         │
│   Discovery = GitHub search + "canonic-verified" topic          │
│   Badge = "✓ CANONIC VERIFIED"                                  │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

The paper that describes this discovery was written using the system it describes, validated by VaaS, and will be distributed through the channel it discovered while being written.

---

## 2. Freeze Reference

| Field | Value |
|-------|-------|
| Freeze tag | `v0.1` |
| Freeze timestamp | 2026-01-17 |
| Freeze commit | (pending) |
| Evidence window | v0.1 |

---

## 3. Publication Targets

### 3.1 Academic

| Target | Artifact | Status | Timeline |
|--------|----------|--------|----------|
| arXiv | CANONIC Paper v0.1 | Pending | Post-freeze |
| Journal (TBD) | CANONIC Paper v1.0 | Planned | Post-v1.0 |

### 3.2 Technical Community

| Target | Artifact | Format | Status | Timeline |
|--------|----------|--------|--------|----------|
| Hacker News | CANONIC announcement | Show HN post | Planned | Post-arXiv |
| GitHub | canonic-machine org | Public repos | Ready | Post-patent |
| Dev.to | Technical deep-dive | Article series | Planned | +2 weeks |

### 3.3 Professional Network

| Target | Artifact | Format | Status | Timeline |
|--------|----------|--------|--------|----------|
| LinkedIn | Announcement | Post | Planned | Same day as HN |
| LinkedIn | VaaS introduction | Article | Planned | +1 week |
| LinkedIn | App Store vision | Article | Planned | +2 weeks |
| Twitter/X | Thread | Multi-tweet | Planned | Same day as HN |

### 3.4 Industry

| Target | Artifact | Format | Status | Timeline |
|--------|----------|--------|--------|----------|
| AI Governance Summit | Presentation | Talk | Planned | TBD |
| Enterprise contacts | VaaS demo | Direct outreach | Planned | Post-arXiv |

---

## 4. Publication Sequence

```
FREEZE (v0.1)
    │
    ▼
PATENT FILING ──────────────────────────────────────────────────►
    │
    ▼
arXiv SUBMISSION ───────────────────────────────────────────────►
    │                                      (wait for acceptance)
    ▼
PUBLIC ANNOUNCEMENT ────────────────────────────────────────────►
    │
    ├──► Hacker News (Show HN: CANONIC - Constitutional AI Governance)
    │
    ├──► LinkedIn (same day)
    │
    ├──► Twitter/X (same day)
    │
    └──► GitHub repos public (same day)
    │
    ▼
FOLLOW-UP CONTENT ──────────────────────────────────────────────►
    │
    ├──► Week 1: Technical deep-dive (Dev.to)
    │
    ├──► Week 2: VaaS introduction (LinkedIn article)
    │
    └──► Week 3: App Store vision (LinkedIn article)
    │
    ▼
ENTERPRISE OUTREACH ────────────────────────────────────────────►
    │
    └──► Direct demos to early access candidates
```

---

## 5. Content Templates

### 5.1 Hacker News (Show HN)

```
Show HN: CANONIC – Constitutional AI Governance That Proves Itself

We built a governance framework for AI systems that:
- Uses 3 axioms (Triad, Inheritance, Introspection)
- Validates itself with 89 deterministic validators
- Generates patent claims from drift detection
- Produced 135 inventions through normal operation

The paper was written using the system it describes.
Every claim is traceable to git commits.

arXiv: [link]
GitHub: github.com/canonic-machine

Built with Claude. Governed by CANONIC. Self-proving.
```

### 5.2 LinkedIn Announcement

```
Announcing CANONIC: Constitutional AI Governance

After 168 AI-assisted sessions, we've built something unusual:
a governance framework that proves itself by running.

3 axioms → 89 validators → 135 inventions

The paper demonstrates what it describes.
Every claim traceable to evidence.

Full paper: [arXiv link]
Open source: github.com/canonic-machine

#AIGovernance #CANONIC #ConstitutionalAI
```

### 5.3 Twitter/X Thread

```
1/ Announcing CANONIC: Constitutional AI Governance 🧵

We built an AI governance framework using AI.
It validates itself. It generates patents.
It proves itself by running.

2/ Three axioms:
- Triad (CANON + VOCAB + README)
- Inheritance (governance flows down)
- Introspection (all terms defined)

3/ 89 validators enforce these axioms deterministically.
Same input = same output. Always.

4/ 135 inventions discovered through normal operation.
Drift → Validator → Patent → Enforcement.
The system reveals its own enforcement gaps.

5/ The paper was written using CANONIC.
Every claim traceable to git commits.
The paper proves itself by running.

arXiv: [link]
GitHub: github.com/canonic-machine

6/ Coming soon: VaaS (Validators as a Service)
Bring your cloud ledgers to CANONIC.
Your repos → governed evidence.

#AIGovernance #CANONIC
```

---

## 6. Time-to-Publication Tracking

Per PUBLISHING Axiom 3, all publications MUST disclose:

| Publication | Freeze | Published | Elapsed |
|-------------|--------|-----------|---------|
| arXiv v0.1 | 2026-01-17 | TBD | TBD |
| Hacker News | 2026-01-17 | TBD | TBD |
| LinkedIn | 2026-01-17 | TBD | TBD |
| Dev.to | 2026-01-17 | TBD | TBD |

---

## 7. Dependencies

```
PATENT FILING ─────► arXiv ─────► Public Announcement
                         │
                         └─────► All social/professional posts

No publication before patent filing.
arXiv gates all public announcements.
```

---

## 8. Success Metrics

| Metric | Target | Measurement |
|--------|--------|-------------|
| arXiv downloads | 1000 | First 30 days |
| Hacker News points | 100+ | First 24 hours |
| GitHub stars | 500 | First 30 days |
| LinkedIn impressions | 10K | First week |
| VaaS inquiries | 10 | First 30 days |

---

## 9. Evidence Links

| Claim | Evidence |
|-------|----------|
| 89 validators operational | `validators/vaas.py` run 2026-01-17 |
| 55 scopes passing | VaaS summary output |
| 136 IDFs | `patents/disclosures/` + IDF-136 |
| 86 atomic axioms | T/I/N decomposition (PA-000, PA-001, PA-002) |
| 168+ episodes | `writing/episodes/` |
| Self-proving paper | `paper/PAPER.md` Section 8 (Conclusion) |
| GitHub = App Store | `paper/PAPER.md` Section 7.7 (Ouroboros) |
| Self-discovering distribution | IDF-136, Episode 168+ |

---

## 10. Cross-Reference

All specifications are synchronized as of 2026-01-17:

| Document | Key Metrics | Status |
|----------|-------------|--------|
| [PAPER.md](/paper/PAPER.md) | 89 validators, 135 IDFs | ✓ Synced |
| [CATALOGUE.md](/validators/CATALOGUE.md) | 89 validators, 55 scopes | ✓ Synced |
| [FOUNDATION.md](/companies/foundation/FOUNDATION.md) | 135 IDFs, 89 validators | ✓ Synced |
| [SCHEDULE.md](/publishing/SCHEDULE.md) | 89 validators, 135 IDFs | ✓ Synced |

---

**This SCHEDULE governs publication timing and content.**
**It carries no governance beyond PUBLISHING CANON.**

---
