# Laya Cycle Dashboard

Self-contained static dashboard for the real Laya decision-model game runs.

## Preview

From this directory run:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish with GitHub Pages

Put the files in this directory at the root of a GitHub repository, enable Pages from the `main` branch and `/` folder, and the dashboard will load `data.json` relative to the site. `index.html` has an offline fallback; hosted pages use the saved JSON record.

The page reports only actual Laya inference cycles. Prior heuristic game results are excluded.
