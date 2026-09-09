Portable data Sync fix

Sync now uses the shipped parsers and bundled Node runtime from the current installation folder, including moved installations and VM paths with spaces. Downloads are validated in a temporary folder and saved in a separate catalog cache so Sync does not modify files managed by the updater. The dashboard and Brain read the refreshed catalogs. Failed downloads preserve the previous data.

Verified with 36 focused tests, a production dashboard build, and a real public-data sync from an isolated relocated installation.
