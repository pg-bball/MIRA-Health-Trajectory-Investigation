# MIRA — Trajectory Turning-Point Investigator

**Health changes gradually. MIRA finds the moments that changed its direction.**

### The problem
Longitudinal records contain years of labs, symptoms, treatments, visits and life events, but they rarely explain *when a health trajectory actually changed*. Current AI tools often summarize records or answer questions; they can also suffer from hindsight bias—using later outcomes to explain what should have been known earlier.

### The innovation
MIRA treats health as a **trajectory investigation**, not a snapshot. It identifies meaningful turning points, investigates the evidence around them, reconstructs what was knowable at that historical moment, and then checks whether subsequent actions were followed by recovery or continued reversal.

### Core method
**State → Signal → Turning Point → Evidence → Action → Outcome → New State**

Evidence is labeled **Observed, Associated, Contradictory, Unknown, or Hypothetical**. A historical “hindsight firewall” prevents later events from leaking into the evidence available at an earlier decision point.

### Prototype workflow
**Find the change → Investigate why → Ask what was knowable then → Act/review → Re-measure → Verify recovery**

The prototype demonstrates a synthetic patient whose trajectory improves, reverses, and can enter a recovery loop. MIRA surfaces the change, explains the surrounding evidence, proposes appropriately bounded next-step categories, and waits for later measurements before calling recovery sustained.

### Why it matters
A warning is useful only if it changes what happens next. MIRA connects **trajectory detection to response verification**, while keeping clinical decisions with qualified professionals.

### Validation plan
A synthetic benchmark will contain known trajectory states, turning points, reversals, recovery, resilience, contradictory signals, delayed evidence, and intervention responses. Evaluation will measure:
- turning-point precision/recall
- reversal detection
- evidence classification agreement
- hindsight separation
- recovery verification accuracy

### Safety & scope
MIRA is a research/education prototype, not a diagnostic or treatment system. No real patient data is included. Any future clinical version would require privacy/security review, expert validation, prospective evaluation and regulatory assessment.

**Team prototype:** MIRA | **Submission:** UnivaBio AI/Technology for Human Health
