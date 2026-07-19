# Koma Shot releases

This public repository is the official download and automatic-update channel for
Koma Shot. The commercial application source is maintained separately; this
repository exists so Windows installers and signed updater metadata can be
downloaded without a GitHub account.

No production release has been published yet. A release is made public only
after its Windows Authenticode signatures, Tauri updater signature, checksums,
and bundled third-party notices have passed the release checks.

## Downloading

When a stable release is available, use the repository's
[Latest release](https://github.com/MorsRead/koma-shot-releases/releases/latest)
page. Website and in-app download links use GitHub's `releases/latest` route, so
they follow the newest published non-prerelease automatically.

Each Windows release contains:

- `Koma-Shot-x64-setup.exe` — the current-user installer and updater payload.
- `latest.json` and `Koma-Shot-x64-setup.exe.sig` — signed automatic-update
  metadata.
- `SHA256SUMS.txt` — SHA-256 checksums for the published files.
- FFmpeg notices and corresponding-source/build materials required for the
  bundled recording runtime.

Draft releases are incomplete and are never offered to the application. Release
assets are immutable after publication.

## Security

Please report a suspected vulnerability privately through this repository's
Security tab. Do not include sensitive details in a public issue.
