# Claude Code Spinner

A single-file web tool for creating Claude-style loading spinner assets. Open `index.html` in a browser, tune the message, colors, motion, and export settings, then download a GIF or PNG.

## Features

- Live canvas preview for the spinner animation
- GIF export with configurable FPS, duration, width, and height
- PNG export for the current frame
- Opaque or transparent background mode
- Preset and custom accent colors
- Shimmer direction, width, speed, and intensity controls
- Light and dark themes with circular reveal transition
- English and Chinese UI switching
- No build step or external runtime required

## Usage

1. Open `index.html` directly in a modern browser.
2. Enter custom text, or leave the message empty to auto-cycle verbs.
3. Adjust color, shimmer, size, FPS, and duration settings.
4. Use `Export GIF` or `PNG` to download the asset.

Theme and language preferences are saved in `localStorage` when available.

## Browser Notes

The circular theme reveal uses the View Transition API when supported. Browsers without this API still switch themes normally, without the reveal animation.

## Files

- `index.html`: complete app, styles, canvas renderer, GIF encoder, and UI logic
- `README.md`: project overview and usage notes
