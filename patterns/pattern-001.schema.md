# Pattern 001 — Column Semantics

This schema defines meaning, not validation.

No column is mandatory by force.
Absence is allowed.
Silence is allowed.

Columns:

- timestamp_utc
  A human-readable UTC timestamp.
  Precision is not required.

- context
  Situational framing of the observation.

- action
  The action that occurred, not the intention.

- residual_signal
  What remained after the action concluded.

- pressure_expression
  How pressure manifested, if at all.

- open_note
  Free-form reflection.

This schema may evolve without breaking the pattern.

---

RX-HCM
