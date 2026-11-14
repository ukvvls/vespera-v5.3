# VESPERA V5.1 — Quest Glass System

A standalone VESPERA build that keeps the existing local-first tools and adds a mature, game-inspired interface: layered liquid-glass panels, a player HUD, subtle quest-style details, and a floating 3D glass navigation dock at the bottom on both desktop and mobile.

## Files
- `index.html` — complete responsive app and interface.
- `manifest.webmanifest` — installable PWA metadata.
- `sw.js` — offline app-shell cache.
- `icon.svg` — blue-on-black liquid-glass 3D app icon.

## Main features retained
- Arabic and English interface.
- Daily tasks, task library, completion tracking, XP, and E–S player ranks.
- Built-in local assistant for planning today’s tasks, arranging selected tasks, showing overdue tasks, suggesting the next task, and adding simple tasks.
- Fitness and activity log, exercise library, profile fields, informational BMI calculation, and seven-day activity chart.
- Local storage, JSON backup import/export, no account/login, and offline app-shell caching.
- Blue/pink accent switching.

## Design update
- Mature game-system / RPG-inspired visual language without childish graphics.
- Dark interface with blue-black glass surfaces, reflections, depth, and restrained glow.
- Floating 3D glass navigation dock fixed at the bottom across screen sizes.
- Player rank emblem and XP progress styled as a system HUD.
- Responsive layouts and reduced-motion support.

## Local assistant and privacy
The assistant uses local commands and app data only. No cloud AI, external AI API, login, or account is required. App data stays in browser local storage. Export a backup before clearing browser data. BMI is informational only and does not affect XP or rank.

## Run
Open `index.html` in a modern browser. For installation and offline caching, publish the folder to a static HTTPS host such as GitHub Pages.
