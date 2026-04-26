# Studio Planner V2.1

A standalone browser-based studio floor planning tool for production layouts.

## Features

- Scaled studio floor layout in meters
- Snap-to-grid placement
- Draggable lights, softboxes, practicals, cameras, subjects, monitors, walls/flats, and green screen blocks
- Fixture presets
- Beam spread controls
- Measurement lines
- JSON save/load
- On-plane technical labels:
  - Light intensity percentage
  - Light Kelvin value
  - Camera lens focal length
  - Camera aperture
  - Camera white balance

## Run Locally

Open `index.html` in any modern browser.

No build tools, server, or dependencies are required.

## Deploy to GitHub Pages

1. Create a new GitHub repository.
2. Upload the files to the repository root.
3. Go to **Settings → Pages**.
4. Choose **Deploy from a branch**.
5. Select branch `main` and folder `/root`.
6. Save.

GitHub will generate a live URL after deployment.

## File Structure

```text
studio-planner/
├── index.html
├── README.md
├── LICENSE
└── .gitignore
```
