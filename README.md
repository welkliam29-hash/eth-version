# eth-version

Version file for Escape the Heist. The game reads `version.json` on start.

- `latestVersion`: newest version (older builds get a hint but may still play)
- `minVersion`: builds older than this must update
- `latestBuild`: build ID of the newest build (e.g. `1112-1435`); leave empty to skip the check
