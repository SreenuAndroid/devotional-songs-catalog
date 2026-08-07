# Devotional Songs catalog (భజన గీతాలు)

Static JSON catalog for the Android app.

## Layout
- `manifest.json` — category index + versions
- `categories/*.json` — songs per deity/section

## Sync
1. App downloads `manifest.json`
2. Compares each category `version` with local cache
3. Downloads only changed category files

## Source
Generated from `Devotional Songs.pdf` (166 songs).
