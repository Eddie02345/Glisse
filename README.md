# Glisse

A private, on-device PDF reader with an adaptive fixation reading mode.

Glisse runs entirely in your browser. Drop a PDF onto the page and read it in two views:

- **Canvas Mode** — renders the original pages at full fidelity.
- **Glisse Mode** — extracts the text layer and sets a bold anchor at the start of every word, giving your eye a place to land and a rhythm to follow.

Nothing is uploaded. Your document stays on your device.

## Features

- On-device PDF rendering via [PDF.js](https://mozilla.github.io/pdf.js/)
- Adjustable fixation intensity, text size, line height, measure, and typeface
- Light, dark, and sepia themes
- Page navigation, drag-and-drop, and password-protected document support
- Responsive layout for desktop and mobile

## Usage

Open `index.html` in a modern browser, or serve the folder with any static file server:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## License

No license specified.