# Devpost Submission Copy

## Project name
MIRA — Trajectory Turning-Point Investigator

## Tagline
Health changes gradually. MIRA finds the moments that changed its direction.

## Inspiration
Healthcare records tell us what happened, but rarely make it easy to understand how a person's health trajectory changed. A value can be abnormal without being a turning point; a later diagnosis can make an earlier event look obvious even though it was not knowable then. MIRA focuses on the missing layer: reconstructing trajectory change without hindsight bias.

## What it does
MIRA converts a longitudinal timeline into a structured investigation. It identifies candidate turning points, gathers the evidence around each point, labels evidence as observed/associated/contradictory/unknown/hypothetical, reconstructs what was knowable at that moment, and checks whether a later action is followed by recovery or continued reversal.

## Why it is different
MIRA is not a generic health chatbot, report summarizer, symptom checker, biological-age calculator, or dashboard. Its core computational object is the health trajectory and its turning points. The prototype uses a hindsight firewall so future information cannot be silently used to explain an earlier decision point.

## How it works
1. Represent longitudinal data as states and signals.
2. Detect meaningful directional changes.
3. Identify surrounding evidence and contradictions.
4. Freeze the evidence window at the historical decision point.
5. Compare later information only as evidence evolution.
6. Track action/outcome response and detect reversal or recovery.
7. Verify whether the new direction is sustained before declaring recovery.

## Health impact
The goal is to make longitudinal change understandable and actionable without replacing clinicians. In a validated future version, MIRA could help patients and care teams notice important trajectory reversals earlier, understand why a change mattered, and verify whether an intervention was followed by sustained improvement.

## Implementation
The submitted prototype is a self-contained browser application using synthetic longitudinal data. The research design includes a benchmark with known turning points, reversals, recovery, resilience, contradictions, delayed evidence, and intervention responses. Proposed evaluation includes turning-point precision/recall, reversal detection, evidence classification agreement, and hindsight-separation tests.

## Limitations
No clinical effectiveness claim is made. No real patient data is included. No diagnosis or prescription is generated. Clinical deployment would require privacy/security controls, prospective validation, expert review, and applicable regulatory assessment.
