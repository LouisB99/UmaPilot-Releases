# UmaPilot v0.1.20

- Fix the Include slot A/B in the loop checkbox being rejected while Continuous Pilot is on. Save only that future seed-build preference, preserving current progress, approved veteran IDs and other project data.
- Safely merge the checkbox change if Pilot updates the project during saving, without resetting its analysis or requiring a reload.
- Recheck the latest option after the Home refresh so turning it off cannot be overwritten by an in-flight operation. Seed insertion still happens only at a safe career boundary.

Validated with 36 targeted tests, the actual checkbox persistence path in an isolated browser with an injected concurrent-save conflict, responsive UI checks and a production build. Other active-project edit protections remain enforced. No personal settings, credentials or account data are included.
