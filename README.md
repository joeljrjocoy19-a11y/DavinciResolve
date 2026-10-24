# Resolve Studio (Prototype)

A browser-based video-editing UI prototype inspired by professional nonlinear editors. This is an independent project and is **not affiliated with or endorsed by Blackmagic Design**. It does not use DaVinci Resolve source code or proprietary assets.

## Features in this starter
- Dark editing workspace with media pool, viewer, inspector, and multi-track timeline
- Import local image, video, and audio files for preview in the current browser session
- Editable title card, accent color, background, and size controls
- Add basic video/title/audio timeline placeholders
- Export a lightweight project-plan JSON file
- Responsive layout for mobile and desktop

## Run
Open `index.html` in a modern browser, or enable GitHub Pages for this repository.

## Enable GitHub Pages
1. Open repository **Settings → Pages**.
2. Under Build and deployment, choose **Deploy from a branch**.
3. Choose branch `main` and folder `/ (root)`, then Save.
4. Wait for the Pages URL to appear in Settings → Pages.

## Current limitations
This is a UI prototype, not a complete nonlinear editor. It does not yet render/export a finished video, perform frame-accurate trimming, mix audio, or provide professional color grading/VFX. The Export button explains this limitation; Save JSON downloads the project plan only. Media is handled locally in the browser session and is not uploaded to a server.

## Roadmap
1. Add real clip metadata and timeline duration controls.
2. Add timeline drag/reorder and trimming.
3. Integrate a browser-supported rendering engine or a server-side FFmpeg worker.
4. Add project persistence and accessible keyboard shortcuts.
5. Add tests and security review before public production use.
