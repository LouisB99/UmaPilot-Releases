Fix the Pilot connection handoff after Data Link.

After restoring a different Trainer ID, Pilot now starts a fresh session for the restored account. Previously it reused the pre-link session identifier, which could reject the next connection on a fresh VM or after switching accounts.

- Saved Trainer IDs and passwords remain usable; no credential re-entry is required for this fix.
- No account reset or automatic retry is introduced.
- 70 regression tests passed, including fresh, switched and matching account handoffs. Session headers also matched two successful official-client capture sequences in offline replay.

Choose Check for updates, then quit UmaPilot from its tray menu and reopen UmaPilot.exe. Confirm v0.1.1 in the dashboard before connecting again.
