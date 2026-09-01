# Device disable markers

This public directory contains de-identified, device-bound disable markers for unsupported test builds of Yongqian Plan.

- File names are SHA-256 hashes of normalized app-scoped device codes.
- Marker files contain no bill data and no plaintext device code.
- Missing or invalid markers are treated as enabled by the app.
- Files are written only by the local admin service; no GitHub credential is bundled in the APK.
