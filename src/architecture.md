# MIRA Architecture

## Core representation

MIRA models longitudinal health as:

**State → Signal → Turning Point → Evidence → Action → Outcome → New State**

## Investigation layers

1. **Baseline** — establishes an individual's prior trajectory rather than assuming a universal normal.
2. **Signal detection** — identifies meaningful directional changes and avoids treating every fluctuation as a turning point.
3. **Turning-point engine** — ranks candidate moments where the trajectory materially changes.
4. **Evidence model** — organizes observations and distinguishes evidence strength/uncertainty.
5. **Hindsight firewall** — historical investigations only use information available at the selected point in time.
6. **Trajectory recovery loop** — follows improvement, drift, reversal and recovery.
7. **Verification** — requires subsequent measurements before calling a recovery sustained.

## Safety boundary

MIRA does not diagnose, prescribe, or claim that temporal association proves causation. Hypothetical alternatives are explicitly labeled as hypothetical.
