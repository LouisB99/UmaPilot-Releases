UmaPilot now checks for updates before starting the dashboard and bot services.

If a new version is available, the startup window shows download progress, the signed update installs, and UmaPilot opens the updated version automatically. No second manual restart is needed for updates found at startup.

- Offline or failed checks open the installed version; startup checks have a two-minute timeout.
- Startup can be cancelled without starting the app.
- Reopening an already-running instance does not interrupt Pilot or Janus. Active services are never stopped for an update.
- Existing rollback and signature checks remain in place. A failed installation restores and opens the previous version.

63 updater tests passed, including a real Windows startup-check/installer handoff, offline and timeout fallback, cancellation, shared download-lock waiting, active-service protection and rollback before opening.

Install 0.1.4 once through the existing updater. On subsequent fresh starts, checking, installing and opening happen automatically in one launch.
