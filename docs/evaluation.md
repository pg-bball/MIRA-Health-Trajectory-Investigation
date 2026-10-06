# Evaluation & Benchmark Plan

## Synthetic benchmark
Generate longitudinal cases with 5–20 years of synthetic observations. Each case includes age/life-stage, health signals, interventions/actions, contextual events, contradictions, missingness, delayed evidence, known trajectory states, and labeled turning points.

### Required case classes
1. Stable baseline
2. Gradual deterioration
3. Gradual improvement
4. Improvement → reversal
5. Deterioration → recovery
6. Resilience after adverse event
7. False alarm / transient fluctuation
8. Contradictory signals
9. Delayed diagnosis / evidence evolution
10. Multiple concurrent trajectories

## Metrics
- Turning-point precision, recall and F1
- Direction-change detection accuracy
- Reversal detection sensitivity/specificity
- Evidence-label agreement
- Hindsight separation: performance when restricted to evidence available at time t
- Recovery verification accuracy
- Calibration/uncertainty reporting quality

## Ablation tests
Compare:
A. trajectory engine with hindsight firewall
B. same engine with future information allowed
C. generic chronological summarization baseline
D. rule-only turning-point baseline

The hypothesis is that MIRA's explicit temporal/evidence representation reduces hindsight leakage and improves turning-point identification over generic summarization.

## Human review
Before any clinical claim, have domain experts review a small de-identified or synthetic sample for whether turning points are plausible, evidence labels are appropriate, and historical reasoning avoids hindsight bias.
