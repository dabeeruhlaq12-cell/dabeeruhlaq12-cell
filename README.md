# Dabeer Ul Haq

I run operations at **Grand Sameer Events** (event infrastructure: domes, hangars, tents) and **Breeze Cooling Solutions** (event cooling) in Ujjain, India. I build the software those businesses actually run on, plus a few public projects, by directing AI coding agents and checking the result against real workflows.

**How I build.** I am not a traditionally trained software engineer. I define the problem from the business side (what breaks on site, what gets lost between the yard and the client), write the rules and acceptance checks, and use AI agents (Claude, ChatGPT/Codex) to write most of the code. Commits co-authored by an AI are left marked as such. My job is the specification, the edge cases, the test data, and deciding what ships.

## Public projects

| Project | What it is | What you can check yourself |
|---|---|---|
| [**Jawabdeh**](https://github.com/dabeeruhlaq12-cell/jawabdeh) | Civic tool for 30 tier-2 Indian cities: which department owns a problem (pothole, water, garbage...), how to complain, and how to escalate. Hindi + English, open JSON dataset where every fact carries a source and a verified / needs-verification status. MIT. | [Live app](https://jawabdeh.vercel.app) · `python3 scripts/validate.py` · CI rebuilds the site from the data on every push |
| [**Frankl upper layers**](https://github.com/dabeeruhlaq12-cell/frankl-upper-layers) | AI-assisted research note on a special case of Frankl's union-closed sets conjecture: an exact averaging criterion, with Lean 4 / mathlib formalization of the stated theorems. The full conjecture remains open; independent review is pending. | Standard-library Python checks + Lean build and axiom audit in CI |
| [**Le Petit Orchestre**](https://github.com/dabeeruhlaq12-cell/le-petit-orchestre) | A pastel theme plugin for the Claude apps: pure SVG + CSS, respects reduced motion. MIT. | Install instructions in the README |
| [**Breeze Cooling Solutions website**](https://github.com/dabeeruhlaq12-cell/Breeze-cooling-solutions) | Static marketing site with an interactive 3D cooling/structure study. Source is visible; no open-source licence yet (company assets). | `python3 -m http.server` |

## Private business systems

These run real company operations, so their code and data stay private. Summaries only:

- **GSE Project Control System:** projects, dispatch, stock, site receipts, documents, costs and audit history for an event-infrastructure company. Node/Next.js, SQLite, automated tests on synthetic data.
- **GSE Command:** a company control dashboard built on it: date-aware inventory reservations, purchase approvals, vendor bills, collections, maintenance and workforce tracking.
- **Breeze Asset Tracker:** QR-code tracking for 80 permanently numbered AC units, with atomic, idempotent batch dispatch. Runs on Cloudflare Workers + D1.
- **Saathra:** a gym membership ERP (multi-tenant, role-based; in development) and an earlier events/gatherings beta at [saathra.in](https://saathra.in).

## What I care about

Small-business software that matches how work happens on the ground in India (WhatsApp-first, Hindi where it helps, works on a cheap phone), and using AI to let one operator build what used to need a team, without pretending the AI didn't do the typing.

Also: music (I release as **Dabeer**), and following AI research closely.
