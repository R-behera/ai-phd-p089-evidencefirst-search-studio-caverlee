# EvidenceFirst Search Studio: Recommender systems for Caverlee-Aligned Research

A research-grade AI/ML PhD preparation project aligned with **James Caverlee** at **Texas A&M University**.

## Research Question

Can retrieval and recommendation systems expose useful evidence and controls without sacrificing ranking quality?

## Advisor Fit

- **Professor:** James Caverlee
- **University:** Texas A&M University
- **Program:** CSE PhD
- **CSV research area:** Recommender systems, IR, data mining, social media
- **Representative paper:** Spam-resilient web ranking work; 2008; WWW
- **Scholar link:** https://scholar.google.com/scholar?q=Spam-resilient+web+ranking+work

## Research-Grade Deliverable

This repo is scaffolded to become a serious research artifact, not a demo-only project. The finished version should include:

- Reproducible dataset pipeline with raw-data provenance.
- Strong baselines and locked experiment configs.
- Original method or evaluation contribution.
- Ablation studies that isolate what changed.
- Failure analysis with concrete examples.
- Paper-style report, limitations, and reproducibility notes.

## Quick Start

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python -m pytest
```

## Repository Map

- `docs/research_brief.md` - project hypothesis, novelty, methods, and evaluation plan.
- `docs/experiment_plan.md` - concrete baseline, ablation, and reporting protocol.
- `configs/baseline.yaml` - first experiment configuration placeholder.
- `src/` - implementation package placeholder.
- `tests/` - smoke and metric tests placeholder.
- `reports/` - figures, tables, and final writeup.
- `reproducibility/commands.md` - exact commands and environment notes.
- `data/source_programs.csv` - original CSV for traceability.

## Status

Scaffolded from the Fall 2027 AI PhD programs CSV. Before external use, re-verify professor interests, application dates, and paper/citation metadata.
