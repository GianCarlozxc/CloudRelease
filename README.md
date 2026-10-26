# Cloud releases

Windows downloads for Cloud, a local desktop IDE.

## Download

[Download Cloud 1.0.1 for Windows x64](https://github.com/GianCarlozxc/CloudRelease/releases/download/v1.0.1/Cloud-Setup-1.0.1.exe)

[All releases](https://github.com/GianCarlozxc/CloudRelease/releases)

1. Download and run `Cloud-Setup-1.0.1.exe`.
2. Follow the installer and launch Cloud.
3. Install the compiler/runtime required by your project; Cloud's Languages & runtimes page shows what is available.

The release includes `SHA256SUMS.txt` for integrity verification. In PowerShell, use `Get-FileHash .\Cloud-Setup-1.0.1.exe -Algorithm SHA256` and compare the result.

## Included

- Multi-language editor, project browsing, saved drafts and session recovery.
- GitHub account switching, account-specific Git authentication, repository contributors and recent commit activity.
- C#/Blazor startup projects, run configurations, debugging and test tools.
- SQLite, MySQL/MariaDB and PostgreSQL connections and queries.
- Embedded localhost preview that opens automatically for responding web apps started with Run.
- Editor preferences, customizable keyboard shortcuts and four appearance themes.

## Source

Application source is maintained in [GianCarlozxc/Cloud](https://github.com/GianCarlozxc/Cloud) (repository access required). This repository contains release information and downloadable builds. Download the installer above to run Cloud.

## In-app updates

Version 1.0.1 adds **Settings > Check for updates**. Cloud detects new stable releases, downloads the update inside the app, and offers **Restart and install**. Recovery drafts are saved before restart. Version 1.0.0 users must run the 1.0.1 installer once to enable future in-app updates.
