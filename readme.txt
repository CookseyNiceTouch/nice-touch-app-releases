Nice Touch — NT-APP Releases

This repository hosts signed installers and update artifacts for the Nice Touch desktop app (Electron).
It is artifacts-only — source code lives elsewhere.

Downloads
Latest stable (recommended)

Use the “Latest” release on the right, or direct links (replace <org>/<repo> with yours):

Windows (.exe)

https://github.com/<org>/<repo>/releases/latest/download/NiceTouch-<version>.exe


macOS (.dmg or .zip)

https://github.com/<org>/<repo>/releases/latest/download/NiceTouch-<version>.dmg


Filenames may vary slightly depending on your packaging targets (e.g., .zip on macOS).
For a specific version, swap latest for a tag, e.g. /releases/download/nt-app@0.0.1/…

Staging / pre-releases (alpha/beta)

Pre-releases are visible under the Releases tab. These are for testers and may be unstable.

What’s included in each release

Installers per platform (Windows .exe, macOS .dmg/.zip)

Update metadata (e.g., latest.yml, latest-mac.yml) and blockmaps for delta updates

Release notes summarising changes

Verify integrity (optional)

We publish file sizes and may include SHA-256 checksums in release notes.
To verify locally:

# macOS / Linux
shasum -a 256 <installer-file>

# Windows (PowerShell)
Get-FileHash <installer-file> -Algorithm SHA256


Compare the output to the checksum shown in the release notes (if provided).

Support & feedback

Problems installing or updating? Please comment on the relevant Release or open an issue in the main app repository.

Security: If you suspect a compromised binary, contact us via our security channel (see company site) and avoid installing that version.

Note: This repo is only for distributing NT-APP builds. For roadmap, issues, and source code, see the main Nice Touch repositories.
