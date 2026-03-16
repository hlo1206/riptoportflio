# RiPto Dev - Portfolio

A pre-built static React portfolio website featuring 3D graphics (Three.js/WebGL).

## Project Structure

This is a compiled React app — all files are already built and ready to serve:
- `index.html` — entry point
- `js/main.99fea1dd.js` — bundled JavaScript
- `css/main.9b103ea3.css` — bundled styles
- `fonts/` — custom fonts (ClashDisplay)
- `images/` — favicon and icons

## Running the App

The app is served as static files using the `serve` package on port 5000.

**Workflow:** "Start application"  
**Command:** `npx serve -s . -l 5000`

## Deployment

Configured as a **static** deployment with `publicDir: "."` since the files are pre-built.

## Tech Stack

- React (pre-built/compiled)
- Three.js / WebGL (3D graphics)
- Custom fonts (ClashDisplay, Inter, Sora via Google Fonts)
