Adds signed automatic updates to the Windows portable edition.

UmaPilot checks after startup and every 15 minutes, downloads changed application files, and installs them when you quit and reopen UmaPilot. Running bots are never stopped by the updater. Accounts, settings, projects, rosters, and results are preserved.

For the original September 9 portable package, download **UmaPilot-Enable-Updates.zip** (about 58 KB). Close UmaPilot, run **Enable-Automatic-Updates.exe**, and select UmaPilot.exe in your existing folder. This is a one-time setup; there is no need to transfer the complete package again.

The updater verifies signed manifests and file hashes, backs up changed application files, and rolls back if offline validation fails. The tray menu includes **Check for updates**.

Validation: 36 targeted tests passed, plus 12 launcher checks. The actual add-on installed into a copy of the original portable package, preserving all 280 saved-data files byte-for-byte; the updated EXE passed cold startup and shutdown. Testing on your actual VM remains to be done.

The other assets are consumed automatically by the updater. These release files contain no personal saved data or private signing keys.
