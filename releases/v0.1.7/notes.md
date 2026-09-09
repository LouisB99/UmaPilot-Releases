# UmaPilot v0.1.7

Fix automatic reconnection reporting another account when the same profile has an expired connection.

- Close the same profile's invalid session worker before reconnecting.
- Keep valid existing connections and preserve the guard against switching a different connected profile.
- Preserve accepted career results; reconnection never repeats finalization.
- Show the original optional sticker failure in the activity log when it causes a disconnect.

Verified with 63 offline tests, including ten successive expired connections, delayed old-worker shutdown, and a completed career followed by a sticker failure. No live career or account action was performed during testing.
