# WallHUD

Small browser HUD for a wall/projection display. The current page combines a minimal transit-prediction widget with simple full-screen display styling.

## What is here

- `index.html` - static page and inline widget markup/styles
- `script.js` - browser-side behavior
- `style.css` - supporting styles

## Run locally

Serve the folder with any static server:

```sh
python3 -m http.server 4173
```

Then open:

```text
http://localhost:4173
```

## Notes

- The page fetches live prediction data from a third-party transit API.
- If that API key, stop code, or service changes, the widget can show `Failed to load predictions`.
- This is best treated as a small display prototype rather than a production transit dashboard.
