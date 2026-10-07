# NAM English v4.1 (iPhone voice fix)

This patch fixes the robotic/alien-like voice heard on iPhone for the newly added cards.

Changes:
- Removed generated MP3 files 059–062.
- Cards 059–062 now use the iPhone's built-in English voice.
- Prefer common natural-sounding en-US voices when available.
- Playback rate adjusted to 0.90.
- Service-worker cache version bumped so the old audio is not reused.

Keep your existing audio/001.mp3 through audio/058.mp3.

After uploading:
1. Replace index.html and service-worker.js.
2. Delete audio/059.mp3 through audio/062.mp3 from GitHub if present.
3. Open the site in Safari once while online.
4. Close/reopen the Home Screen app. If it still sounds old, remove the Home Screen icon and add it again.
