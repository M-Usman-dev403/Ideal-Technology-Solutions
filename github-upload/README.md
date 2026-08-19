# Ideal Technology Solutions — homepage demos

Three self-contained homepage designs. Each file is standalone (no build step, no dependencies to install).

| File | Demo | Direction |
| --- | --- | --- |
| `index.html` | 1a | Original layout — hero, service pillars, industries, service catalog, process |
| `1b.html` | 1b | Operations desk — fixed left nav rail, live service board, engagement models, FAQ, brief form |
| `1c.html` | 1c | Build it once — full-screen hero, horizontal service rail, interactive lifecycle, selected work, comparison table |

## Deploying with GitHub Pages

1. Create a repository (or use an existing one) and upload these four files to the repository root.
2. Settings → Pages → Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. After a minute the demos are live at:
   - `https://<user>.github.io/<repo>/` (1a)
   - `https://<user>.github.io/<repo>/1b.html`
   - `https://<user>.github.io/<repo>/1c.html`

## Notes

- Responsive from 360px up; navigation, grids and tables collapse to single column on phones.
- Animations respect `prefers-reduced-motion`.
- Fonts load from Google Fonts; everything else is embedded in the file.
- Placeholder figures (uptime, response times, engagement metrics) should be replaced with real numbers before public launch.
