# Word Count Tool Updates

Public release channel for the Windows desktop application.

This repository intentionally contains update metadata and compiled release
packages only. The application source code, server source code, credentials,
database files, and administration files are not published here.

Official website: https://routineoff.com

## Stable channel release rule

`update_manifest.json` is the final production release switch. Do not update it
until all of the following are complete:

1. The full Windows, server, and website test suites pass.
2. The final installer and update ZIP are built from the same version.
3. The installer passes a clean-Windows smoke test.
4. The versioned GitHub Release assets are uploaded and publicly downloadable.
5. The public website shows the same version, filename, size, and SHA-256 value.

Only then copy the signed manifest into this repository and publish it. This
keeps installed customers on the last verified version if a build or deployment
step fails.
