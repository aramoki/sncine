# sncine technical overview

An English, single-page technical overview of the sncine game engine. The site is plain HTML, CSS, and JavaScript and can be published directly with GitHub Pages.

## Screenshots

The page contains nineteen visible screenshot placeholders. Put the PNG files in the `assets` directory using the filenames below. The corresponding placeholder will be replaced automatically; no HTML changes are required. Every loaded image opens in a full-screen viewer when clicked.

- `editor-overview.png`
- `rendering-showcase.png`
- `occlusion-culling.png`
- `shadows-lighting.png`
- `runtime-debug.png`
- `scene-streaming.png`
- `lua-scripting.png`
- `sncpak-content.png`
- `package-editor.png`
- `animation-tools.png`
- `object-picking.png`
- `benchmark-report.png`
- `profiler-timeline.png`
- `gallery-01.png`
- `gallery-02.png`
- `gallery-03.png`
- `gallery-04.png`
- `gallery-05.png`
- `gallery-06.png`

## Local preview

No dependencies are required. Open `index.html` directly or run a local server:

```sh
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## GitHub Pages

Open **Settings → Pages** in the repository. Select **Deploy from a branch**, then choose the `main` branch and `/ (root)` directory.
