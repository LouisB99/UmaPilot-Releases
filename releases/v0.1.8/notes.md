UmaPilot v0.1.8

- Fix Narita Brian race agenda generation: alternate versions of a mandatory race no longer occupy the same calendar slot. Invalid conflicting agendas are rejected before sending a career start.
- Show the actual numbered training order and the parents for each step. Repeated closure-parent steps are distinguishable, with the current step highlighted.

Validation: 63 backend tests, 11 UI logic tests, production build, and browser layout/order checks passed. Tests also verify progression after changing acceptance requirements. No live VM career was started during validation.
