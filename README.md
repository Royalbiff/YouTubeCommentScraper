# The Virtual Post — Idea Terminal

Retro editorial planner for The Virtual Post.

## What it does
- Organizes video ideas by category, status, priority, and editorial score.
- Stores working titles, angles, hooks, thesis statements, notes, and script-outline beats.
- Links seeded ideas back to source research in Google Drive.
- Uses `data.js` as the task-owned canonical feed while browser-local edits remain layered on top.
- Links directly to ChatGPT Scheduled Tasks.

## Automation link
Primary updater: **Virtual Post Trend Brief** (daily).
Research inbox: **Virtual Post Watch Radar** (three times daily).

The daily Trend Brief is instructed to read and merge strong new opportunities into `data.js` when GitHub write access is available.

## Publish with GitHub Pages
In this repository, open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.

The site is fully static: `index.html`, `style.css`, `app.js`, and `data.js`.
