
# Taskify

[![Auto Deploy](https://github.com/Punithnk/Taskify/actions/workflows/auto-deploy.yml/badge.svg)](https://github.com/Punithnk/Taskify/actions/workflows/auto-deploy.yml) [![Website](https://img.shields.io/badge/website-online-brightgreen)](https://Punithnk.github.io/Taskify/)

[Live demo](https://Punithnk.github.io/Taskify/) • A minimal, friendly React task manager built with Vite.

Taskify is a compact, component-driven todo app meant for learning and quick customization. Add tasks with priority and category, mark them complete, delete them, and watch a live progress bar that updates as you work.

Why this project
- Small, focused codebase — great for beginners who want to learn React + Vite.
- Accessible and modern UI (plain CSS) with responsive layout.
- Easy to extend: persistence, filters, backend sync, and more.

Live demo
- https://Punithnk.github.io/Taskify/

Quick start (PowerShell)
```powershell
git clone https://github.com/Punithnk/Taskify.git
cd 'c:\Users\punit\Desktop\Front End\Taskify\Taskify'
npm install
npm run dev
```

Build for production
```powershell
npm run build
```

Deploy
- This repository includes a `gh-pages` deployment. The site is published to GitHub Pages at the Live demo link above.

Features
- Add tasks with priority (high/medium/low) and category (general/work/personal).
- Toggle complete / undo for each task.
- Delete single tasks or clear all tasks.
- Progress tracker shows completed tasks and a visual progress bar.

Important files
- `index.html` — App entry point
- `src/main.jsx` — React bootstrap (createRoot)
- `src/App.jsx` — Main layout and state management
- `src/Components/Taskform.jsx` — Add-task form (controlled inputs)
- `src/Components/TaskList.jsx` — List and task actions
- `src/Components/Progresstracker.jsx` — Progress visualization
- `src/Style.css` — Global styles and visual design

Contributing
- Open an issue for larger changes before starting work.
- Keep PRs small and focused. Run `npm run build` and `npm run lint` (if you add linting) before opening a PR.

License
- Suggested: MIT — simple and permissive. Add a `LICENSE` file to apply it.

Contact / Notes
- Want automation or features added (localStorage, tests, CI)? Open an issue or ask here and I can help implement them.





