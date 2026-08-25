# AZK Stremio AniSkip

Morphe patch for Stremio Android that adds `Skip OP`, `Skip ED`, and `Skip recap` buttons while AniSkip segments are playing.

Mod version: **1.1.1**

Repository: <https://github.com/AzukiSensei/aniskip-stremio>

## Features

- Detects the anime title, season, and episode from media metadata and stream URLs.
- Resolves the AniList identifier and retrieves the matching AniSkip segments.
- Shows a skip button only while an opening, ending, or recap segment is active.
- Uses a compact button positioned on the right and centered vertically.
- Keeps debug logging disabled by default.

## Configuration

After adding this repository as a Morphe patch source and selecting **Stremio AniSkip**, enable the debug option in the patch settings when diagnostics are needed. The debug window displays detected media data, API requests, and API responses.

## Build locally

```bash
./gradlew buildAndroid
```

The Android patch bundle is generated under `patches/build/libs/`.

The repository also contains the latest bundle under [`releases/stremio-aniskip-morphe-1.1.1.mpp`](releases/stremio-aniskip-morphe-1.1.1.mpp).

## Morphe source metadata

The release workflow generates `patches-list.json` and `patches-bundle.json` when a semantic release is published. Morphe requires a published bundle release to display the repository name, version, and patch list correctly.

## License

GPLv3 — see [LICENSE](LICENSE).
