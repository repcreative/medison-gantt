# Medison — Gantt Chart

Interactive project Gantt chart for the Medison × GA-DA *Discovery & Interactive Map* project.

A single self-contained page (`index.html`) — no build step, no dependencies to install.

* Drag a bar to move a task; drag its edges to resize.
* Click a row or a bar to open the editor.
* Hover the small **i** at the end of a task title for owner + dates.
* Days / Weeks / Months zoom, search, phase filter, CSV export.

Edits are stored in the visitor's own browser (localStorage) — `↺` resets to the original plan.

> `index.html` and `gantt_app.html` are the same file (hard-linked locally) — edit either one.

## Local preview

```bash
python3 -m http.server 8899
# then open http://localhost:8899
```

## Deployment

Published with GitHub Pages from the `main` branch, repository root.
