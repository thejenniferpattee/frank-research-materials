# frank-research-materials
Research materials for Frank, the AI-assisted screener for ADHD  

## Purpose

This repo contains IRB-aligned research materials for Frank and related coursework research. It includes protocols, measures registry, consent and risk disclosure drafts, references to Qualtrics exports and analysis notebooks, posters, and paper drafts. It contains **no participant data**.

## Status

**Frank Study Phase 1**: IRB approved, preparing for data collection.

## What this repo is:
1. Phase-level study cards and protocols for Frank.
2. Consent, confidentiality, and risk disclosure drafts with version history.
3. Measures registry linking instruments, items, scoring, and provenance to `frank-content`.
4. Writing and presentation artifacts such as posters, figures, and paper drafts.


## What this repo is not
1. Not a dataset repository.
2. No raw responses, transcripts, identifiers, recruitment logs, or contact information.
3. No real participant data. Only synthetic or example data will be used in analysis examples.
4. No code needed to run the Frank app. That lives in `frank-app`.

**What’s real vs planned:**

Real: 
initial JSON placeholders and draft structure.

Planned: 
populate JSON with final content, add one-click demo path.

**Not included on purpose:**

App code, any backend or UI implementation, any real user data.

## How to review in 3 min

1. **status/protocol_status.json** for phase-by-phase status.
2. **status/measures_registry.json** for measures, item sources, and provenance.
3. **irb/README_IRB_PACKET.md** for what is in the IRB packet and how it maps to the protocol.


## Repo structure 

The following folders are used to store different study materials:

- `status/` — Current study phase and protocol status.
- `irb/` — IRB packet and related documentation.
- `protocols/` — Study protocols.
- `consent/` — Consent forms and risk disclosure.
- `measures/` — Measure registry and questionnaire items.
- `analysis/` — Analysis notebooks and results.
- `posters/` — Research posters and presentation materials.
- `papers/` — Research paper drafts.


## Data handling policy
Do not add participant data. If analysis examples are needed, use **fully synthetic data** and label it clearly as synthetic. Store only schemas or toy examples that cannot be traced to real participants.
