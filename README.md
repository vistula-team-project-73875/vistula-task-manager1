# Task Manager — Team Project IT

**Student:** Chkhartyshvili Dmitrii  
**Student ID:** 73875  
**GitHub username:** `vistula-team-project-73875`

## Links

- [Live application](https://vistula-team-project-73875.github.io/vistula-task-manager/)
- [Source repository](https://github.com/vistula-team-project-73875/vistula-task-manager)
- [Team contribution page](https://vistula-team-project-73875.github.io/vistula-task-manager/contribution.html) — available after partner PR is merged
- [Contributor JSON](https://vistula-team-project-73875.github.io/vistula-task-manager/contribution.json) — available after partner PR is merged

## Features

A public Task Manager with persistent tasks stored in Supabase PostgreSQL. Users can view, create, edit, mark complete/incomplete, and delete tasks. All operations use the Supabase REST API directly from vanilla JavaScript.

## Technology

HTML, CSS, JavaScript, GitHub Pages, Supabase (PostgreSQL + REST API).

## Files

- `index.html` — interface and required automated-testing elements
- `style.css` — responsive design
- `app.js` — CRUD operations via `fetch()`
- `config.json` — public project URL, publishable key, and table name
- `contribution.html`, `contribution.json` — **must be added by the partner via a merged Pull Request; do not add these yourself**

## Collaboration (complete after both PRs are merged)

- **My PR to partner's repository:** pending — insert merged PR link here.
- **Partner's PR to this repository:** pending — insert merged PR link here.

## Deployment

GitHub repository → Settings → Pages → Deploy from a branch → `main` / `/(root)` → Save.

## Security

This is a demonstration-only database. Public anonymous CRUD access is enabled intentionally for the assignment. Do not store private or production data. Only a publishable API key is included in the frontend.

## Setup for student 73875

Create a separate Supabase project, run the `tasks` table SQL and public RLS policies, then replace the two placeholder values in `config.json` with your own project URL and **publishable** key. Never commit database passwords or secret/service-role keys.
