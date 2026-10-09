# GPT Swing Radar

Swing Lab v3.19.0 source and release distribution. The application source is in `swing-lab-v3-source.zip`, with its directory layout preserved.

- Stock-name recovery and duplicate-code display fix.
- Validated GitHub release updater with rollback.
- Server checks for updates every five minutes.

No runtime price database, accounts, login credentials or API secrets are included.

The workflow extracts the source archive, validates the version against a `vX.Y.Z` tag, and publishes `release.json` and `swing-lab-v3-update.zip`. The tag must match the version in the source BUILD_MANIFEST.json.

The current server updater uses unauthenticated public releases. A private repository can store these files, but requires a different download-authentication setup before automatic server updates will work.

Initial installation instructions are inside `swing-lab-v3/CHANGES-v3.19.0.md`.
