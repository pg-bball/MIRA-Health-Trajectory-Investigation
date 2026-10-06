# MIRA — Health Trajectory Investigation Engine

> **Finding the turning points that change a person's health trajectory.**

MIRA is a software prototype for investigating longitudinal health trajectories. It identifies meaningful changes in direction, examines the evidence around those turning points, separates contemporaneous evidence from later knowledge, and follows whether a trajectory appears to recover or reverse.

## Core investigation loop

**Detect → Explain → Act → Re-measure → Verify**

## What the prototype demonstrates

- Individual baseline and longitudinal timeline
- Turning-point investigation
- Evidence convergence and uncertainty labels
- Hindsight-aware historical reasoning
- Trajectory reversal detection
- Recovery-loop concepts
- Follow-up verification

## Run locally

No backend, database, API key, or build step is required for the current prototype.

1. Open `prototype/index.html` in a modern browser, or
2. Serve the repository with any static web server and open `/prototype/`.

## Repository structure

```text
MIRA-Health-Trajectory-Investigation/
├── prototype/
│   └── index.html
├── benchmark/
│   └── seed.json
├── docs/
│   ├── demo_script.md
│   ├── evaluation.md
│   ├── one_page.md
│   ├── safety.md
│   ├── submission_text.md
│   ├── SUBMISSION_CHECKLIST.md
│   ├── MIRA_UnivaBio_OnePage.pdf
│   └── MIRA_UnivaBio_Code.pdf
├── src/
│   └── architecture.md
├── tests/
│   └── test_cases.md
├── LICENSE
└── README.md
```

## Data and safety

The competition prototype uses synthetic data and is for research/demo purposes. It is not a medical device, diagnostic system, or substitute for professional medical care. It does not independently prescribe treatment.

## Evaluation direction

The accompanying benchmark and evaluation plan focus on turning-point detection, trajectory reversal detection, evidence classification, hindsight separation, and recovery verification.

## Competition

Prepared for the UnivaBio Technology for Human Health challenge. The project is designed to demonstrate a specific healthcare/technology problem, a working interaction prototype, and an auditable technical approach.
