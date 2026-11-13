# Shoulder Check

ReactForge peripheral vision game for hockey players. The front camera reads head turn; holding a turn steers the player between lanes to dodge blocks and collect stars.

- Play: https://stakano2.github.io/shoulder-check/
- Open in Chrome or Safari on the phone or tablet and allow the camera. In-app browsers and the Claude preview block the camera.
- Settings: same or opposite mapping, 3 or 5 lanes, turn depth 45 to 90 degrees, speed 1 to 5 or auto, star bias left or right.
- Calibration per athlete; per-round metrics (stars, hits, reaction time left and right, max turn, time turned away, wrong-way turns) stored in the browser, exportable as CSV.
- Video stays on the device. Only angles and scores are saved.

Single file (`index.html`). Loads MediaPipe Tasks Vision 0.10.14 and the face landmarker model on first run (about 4 MB).
