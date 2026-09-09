## Pilot Data Link and visible update status

- Encode typed Data Link passwords using the Global client format. Existing encoded credentials remain compatible.
- Previously saved VM credentials are handled without re-entry.
- Show the failed Data Link stage and response/result codes instead of a generic RuntimeError.
- Fix updater catch-up and rollback when intermediate dashboard assets never existed locally.
- Show the installed version beneath the bottom-left connection status.
- Replace the version with download progress while updating, then an Update ready / Please restart notice.

Download using Check for updates in the tray menu, then quit and reopen UmaPilot. This release adds the dashboard indicator; live progress will be visible for subsequent downloads after installation. Saved projects, accounts and results are preserved.
