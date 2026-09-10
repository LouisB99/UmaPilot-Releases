# UmaPilot v0.1.17

- Fix project creation rewriting unrelated projects while Continuous Pilot updates its active career. New projects preserve the active project's exact saved record and checkpoint.
- Background planning updates only its target project. The creation form waits for save confirmation and shows save failures.
- Load saved race agendas and support decks from the connected account instead of developer capture files, so preset selection works on portable installations and VMs.
- Cache agendas separately for each account and reuse them during an active career. Add Refresh saved presets and clear loading, busy, empty and cached states. With no cache yet, agendas can be loaded after the current career is collected.

Validated with 44 backend tests, 32 storage/merge tests, a real-browser creation and agenda regression, and a production build. No live career was started or collected during testing. Personal data and credentials are excluded from this code-only update.
