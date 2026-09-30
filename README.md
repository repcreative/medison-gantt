# Medison — Gantt Chart

Interactive project Gantt chart for the Medison × GA-DA *Discovery & Interactive Map* project.

A single self-contained page (`index.html`) — no build step, no dependencies to install.

* Drag a bar to move a task; drag its edges to resize.
* Click a row or a bar to open the editor.
* Hover the small **i** at the end of a task title for owner + dates.
* Days / Weeks / Months zoom, search, phase filter, CSV export.

Everyone sees one shared version, read from `data.json` in the public repo
[`repcreative/gantt-data`](https://github.com/repcreative/gantt-data).
Editing is locked: **ערוך את הגאנט** asks for the edit password and unlocks editing for one hour;
changes are published for everyone within seconds. The password lives (encrypted) in `edit-lock.json`
in this repo, so only the repo owner can change it. See `HANDOFF.md` → *נתונים משותפים ונעילת עריכה*.

## Local preview

```bash
python3 -m http.server 8899
# then open http://localhost:8899
```

## Deployment

Published with GitHub Pages from the `main` branch, repository root.
