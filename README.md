# Medison — Gantt Chart

Interactive project Gantt chart for the Medison × GA-DA *Discovery & Interactive Map* project.

A single self-contained page (`index.html`) — no build step, no dependencies to install.

* Drag a bar to move a task; drag its edges to resize.
* Click a row or a bar to open the editor.
* Hover the small **i** at the end of a task title for owner + dates.
* Days / Weeks / Months zoom, search, phase filter, CSV export.

Everyone sees one shared version, read from `data.json` in the public repo
[`repcreative/medison-gantt-data`](https://github.com/repcreative/medison-gantt-data).
Editing is locked: **ערוך את הגאנט** asks for the edit password and unlocks editing for one hour;
changes are published for everyone within seconds. See `HANDOFF.md` → *נתונים משותפים ונעילת עריכה*
for how it works, first-time setup, and what the lock does and does not protect.

## Local preview

```bash
python3 -m http.server 8899
# then open http://localhost:8899
```

## Deployment

Published with GitHub Pages from the `main` branch, repository root.
