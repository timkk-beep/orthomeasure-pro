# OrthoMeasure Pro

A single-page, browser-based tool for measuring hip parameters on pelvic X-rays.

**Live demo:** https://timkk-beep.github.io/orthomeasure-pro/

## Measurements

| Tool | Description |
|------|-------------|
| AI | Acetabular Index |
| MP | Reimers Migration Percentage |
| NSA | Neck-Shaft Angle |
| CE | Center-Edge Angle |
| Sharp | Sharp Angle |
| Depth | Acetabular Depth (relative) |

## Usage

1. Open the page and upload an X-ray image.
2. Pick a tool, then drag the landmarks into place. Scroll to zoom, drag empty space to pan, and drag the center crosshair to move the whole tool.
3. Enter a patient name or ID and click **Save**. Saved records can be exported to CSV.

All processing runs locally in the browser. Images are never uploaded, and saved records are kept only in the browser's `localStorage`.

## Run locally

Open `index.html` in a modern browser. It needs an internet connection to load React, Tailwind, Babel and Phosphor Icons from CDNs.

## Credits

Created by [@timkk-beep](https://github.com/timkk-beep), developed with AI assistance from **Google Gemini 3.1 Pro** and **Anthropic Claude**.

## Disclaimer

For research and educational use only. Not a certified medical device.
