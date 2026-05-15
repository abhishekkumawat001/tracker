# Habit Quest Tracker

A dependency-free habit tracker web app inspired by a spreadsheet-style daily check-in board.

## Features

- Monthly habit grid with one checkbox per habit per day
- Editable habit list with icons and target frequency
- Daily, weekday, and weekend schedules
- Month navigation and jump-to-today
- Completed habits, total progress, current streak, and quest score
- Daily progress trend chart
- Complete-today and clear-month actions
- Local browser persistence with `localStorage`
- JSON import and export for backup

## Run Locally

Open `index.html` in a browser, or serve the folder with any static file server.

```bash
npx serve .
```

No build step is required.

## Deploy

Deploy the folder as a static site. Good options:

- Netlify: drag this folder into Netlify Drop
- Vercel: import the folder/repo and use the static default
- GitHub Pages: publish the repository root

The app stores data in the visitor's browser. For cross-device sync, add a backend such as Supabase, Firebase, or your own API.
