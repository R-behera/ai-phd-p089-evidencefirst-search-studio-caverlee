# Unique Prototype Algorithm

## Algorithm

**CaverleeEvidenceRecommenderSystemsRepairLoop** (`P089-Caverlee-RecommenderSystems`)

## Professor Alignment

- Professor: James Caverlee
- Research area: Recommender systems, IR, data mining, social media
- Focus terms: Recommender systems, IR, data mining, social media

## Core Mechanism

This prototype prioritizes ranking cases where relevance, evidence, and controllability diverge.

## Decision Rule

Rank seed cases by retrieval-specific priority score with Caverlee-aligned focus term 'Recommender systems'.

## What The Code Adds

- A unique algorithm spec in `src/proposed_method.py`.
- A scoring function for the repo's `retrieval` data schema.
- A ranked list of cases that should be reviewed, repaired, reproduced, or expanded first.
- Integration into `src/value_add.py`, so demo output includes the proposed method.

## Honest Status

This is a runnable algorithmic prototype. It is not a validated contribution to James Caverlee's published work until the seed data is replaced with real public/lab-relevant data and the resulting claims are evaluated.

## Run

```bash
python src/proposed_method.py
python src/value_add.py --write-report reports/demo_results.json
python -m unittest discover -s tests
```
