Dashboard update checks now request a fresh release feed, avoiding cached responses that still list an older version.

This release includes the automatic dashboard update controls introduced in 0.1.2:
- Check when the dashboard opens, every minute while open, and when returning to its window.
- Check updates directly below the version, without opening the tray menu.
- Download progress followed by Update available / Restart UmaPilot.

55 backend/updater tests passed, plus browser checks of opening, periodic checks and all visible update states. A real background worker verified the public signed download without tray interaction. Existing payload signature verification and download locking remain in place.

For this update, use the current tray Check for updates once or wait for its normal automatic check, then quit and reopen UmaPilot. Future checks run directly from the dashboard.
