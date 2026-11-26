# Pocket Channel — Online Radio & Global Live TV (v32)

Developed by **Azahar Uddin Mondal** (`azaharofficial@gmail.com`).

## What's Fixed in v32
- **Immediate PiP Mode on PiP Icon Tap:** Removed the `tvVideo.requestFullscreen()` branch from `toggleTvPip()` so tapping the PiP icon always enters Picture-in-Picture mode directly instead of opening native video fullscreen.
- **Removed `disableRemotePlayback` & Added Metadata/Play Ready Retry:** Ensures `#tvVideo` can enter native PiP reliably even if tapped right after selecting a channel before metadata finishes loading, with automatic fallback to the floating 16:9 PiP window when native JS PiP is unavailable.

## How to Run
Extract the ZIP folder and open `index.html` in any modern browser, or deploy directly to GitHub Pages.
