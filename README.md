# EvidenceFirst Search Studio: Recommender systems for Caverlee-Aligned Research

A professor-outreach research proposal aligned with **James Caverlee** at **Texas A&M University**.

## For Professor Outreach

This repo is intended to support an honest outreach email. It contains a concrete proposal for what value you can add, but it does **not** yet contain completed experiments or results.

Start here:

- `outreach/value_add_packet.md` - professor-specific contribution plan.
- `outreach/email_draft.md` - short mail draft you can personalize before sending.
- `docs/one_page_project_plan.md` - one-page project summary.
- `PROJECT_STATUS.md` - clear statement of what exists and what does not exist yet.

## Research Question

How can a focused, reproducible artifact around **Recommender systems** create useful research infrastructure for a lab working on **Recommender systems, IR, data mining, social media**?

## Advisor Fit

- **Professor:** James Caverlee
- **University:** Texas A&M University
- **Program:** CSE PhD
- **CSV research area:** Recommender systems, IR, data mining, social media
- **Representative paper:** Spam-resilient web ranking work; 2008; WWW
- **Scholar link:** https://scholar.google.com/scholar?q=Spam-resilient+web+ranking+work

## Proposed Research-Grade Deliverable

Build **a transparent ranking or recommendation system with user-controllable evidence** with:

- Baseline ranking system with reproducible metrics.
- Control/explanation module with ablations.
- Preference-drift or counterfactual evaluation.
- Report on quality-control tradeoffs.

## Quick Start

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python -m pytest
```

## Repository Map

- `outreach/value_add_packet.md` - value-add plan for this professor.
- `outreach/email_draft.md` - email draft; personalize before sending.
- `docs/research_brief.md` - project hypothesis, novelty, methods, and evaluation plan.
- `docs/one_page_project_plan.md` - one-page project summary.
- `docs/experiment_plan.md` - baseline, ablation, and reporting protocol.
- `configs/baseline.yaml` - first experiment configuration placeholder.
- `reproducibility/commands.md` - exact commands and environment notes.
- `data/source_programs.csv` - original CSV for traceability.

## Status

Proposal scaffold only. Before external use, verify the professor's current lab page and make a selected repo public or shareable.
