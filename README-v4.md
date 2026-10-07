# NAM English v4 update

This is an update package for the existing `SetsuoK/nam-english` repository.

## Changes
- Core 30 / All 62 toggle
- Added 30-second self-introduction and 60-second research explanation
- Added two high-value networking/collaboration questions
- MP3-first audio playback, with device speech synthesis only as fallback
- Service worker cache bumped to v4 and includes 001–062 MP3 files
- Existing learned-state data is migrated from V2 when possible

## Upload
1. Replace repository-root `index.html` with this file.
2. Replace repository-root `service-worker.js` with this file.
3. Add `audio/059.mp3` through `audio/062.mp3`.
4. Keep existing `audio/001.mp3` through `audio/058.mp3`, `manifest.json`, `icon-192.png`, and `icon-512.png`.
5. After GitHub Pages redeploys, open once in Safari. If the Home Screen app is stale, remove the Home Screen icon and add it again.
6. Test in Airplane Mode with Wi-Fi OFF.

Note: the four newly generated MP3 files use a local synthetic US-English voice; existing 001–058 files are intentionally not replaced.
