Updates now appear automatically inside the dashboard.

- Opening the dashboard starts an update check. It checks again every minute and when returning to the window.
- A Check updates button below the version allows an immediate check without opening the tray menu.
- The version changes to download progress, then Update available / Restart UmaPilot when ready.
- Multiple tabs and tray checks share the download lock. A staged update stays ready, and running Pilot or Janus jobs are never stopped automatically.

Validated with 54 backend/updater tests, a browser regression covering automatic opening and timed checks, and a real background worker downloading a signed public update without tray interaction.

To receive this first dashboard-check update, use the existing tray Check for updates once or allow its normal automatic check. When ready, quit UmaPilot and reopen it. Subsequent checks work directly from the dashboard.
