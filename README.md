# Breathe v12 — Audio Design Prototype

Built on the existing Breathe app and its Balanced Abstract visual design.

## Audio features
- Optional, low-level synthesized distant-water ambience.
- Independently adjustable water ambience level.
- Gentle multi-part bowl-like chime at breathing phase changes, with its own on/off control and level.
- Optional, low-level stereo binaural tone with an independent level control. Headphones are needed to perceive the stereo frequency difference.
- A short soundscape preview in Settings.
- Audio preferences saved locally on the device.
- Audio is created in the browser with Web Audio, so this prototype does not download or require separate audio files.

The water and bowl sounds are synthesized placeholders, not high-quality field recordings or recorded singing bowls. They are intended to test the control layout and audio behavior before selecting final audio assets. Binaural audio is optional and should not be presented as a treatment or as having guaranteed effects.

## Update on iPad
1. Download and extract the ZIP in Files.
2. Back up the current `index.html` and `sw.js` in your GitHub repository.
3. Replace `index.html` and `sw.js` with the files in `breathe_web_app`.
4. Commit both files to the branch and folder published by GitHub Pages.
5. Open the published site in Safari and refresh it. If you use the Home Screen app, close and reopen it after the website has refreshed.

The service-worker cache is `breathe-shell-v12`.
