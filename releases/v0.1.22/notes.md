# UmaPilot v0.1.22

More detailed training-start diagnostics for investigating game rejection 205.

- Record the saved agenda, compiled race metadata, trainee upgrades, TP recovery timing and seed-loop state.
- Retain separate accepted and failed attempts locally for comparison.
- Keep the existing diagnostic download action and credential exclusions.

This release improves diagnosis; it does not claim to fix rejection 205. No automatic retry of a training start is added. Validation: 40 offline diagnostic, runtime, agenda and seed tests passed.
