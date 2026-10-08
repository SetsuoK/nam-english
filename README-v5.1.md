# NAM English v5.1 — iPhone playback fix

This fixes a no-playback issue on iPhone Safari / Home Screen PWA.

Changes:
- Avoid immediate cancel() -> speak(), which can fail on iOS.
- Use a short delay only if existing speech must be cancelled.
- Call speechSynthesis.resume() before speaking.
- Show playback start/end/error status.
- Keep the voice selector, speed, and pitch controls.

Update:
1. Replace index.html and service-worker.js.
2. Open GitHub Pages once in Safari.
3. Remove the old Home Screen icon.
4. Add the site to Home Screen again.
5. Tap 音声テスト first.
