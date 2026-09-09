UmaPilot v0.1.9

- Reopen the last connected Pilot profile on application startup, independently of continuous career automation. Explicit disconnect disables reconnection. Profiles assigned to Janus, removed profiles, and unavailable sign-ins are not restored.
- Planned lineage trees now reuse the exact approved veterans available in their parent slots. Saved ancestry remains tied to its original veteran IDs.
- Add a Start diagnostic download in the Pilot log. It records the selected training setup and server result without credentials, session tokens, Steam identifiers, or trainer IDs.

The remaining response 205 is still under investigation; this release does not claim to resolve it. The diagnostic provides the VM-specific setup needed to identify the rejected parameter.

Validation: 110 backend tests, 12 UI tests, production build, and browser checks for lineage colors and authenticated diagnostic downloads passed.
