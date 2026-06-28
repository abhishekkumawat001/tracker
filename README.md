# HabitQuest Tracker

![Status](https://img.shields.io/badge/status-active-brightgreen)
![Platform](https://img.shields.io/badge/platform-web-blue)
![Storage](https://img.shields.io/badge/storage-localStorage-orange)
![License](https://img.shields.io/badge/license-open%20source-lightgrey)

A streamlined habit tracker for daily consistency.

> [!NOTE]
> Runs entirely in the browser and stores data locally with `localStorage`.

## Screenshot

![HabitQuest Tracker screenshot](docs/screenshot.png)

## Features

- Monthly habit grid with one checkbox per habit per day
- Editable habit list with icons and target frequency
- Daily, weekday, and weekend schedules
- Month navigation and jump-to-today
- Completed habits, total progress, current streak, and quest score
- Daily progress trend chart
- Complete-today and clear-month actions
- JSON import and export for backup

## Run Locally

Open `index.html` in a browser, or serve the folder with any static file server.

```bash
npx serve .
```

No build step is required.

## Deploy

Deploy the folder as a static site. Good options:

- **Netlify**: drag this folder into Netlify Drop
- **Vercel**: import the folder/repo and use the static default
- **GitHub Pages**: publish the repository root

> [!TIP]
> Data lives in the visitor's browser. For cross-device sync, add a backend such as Supabase, Firebase, or your own API.

## Overview

HabitQuest Tracker gives you a clean visual calendar, progress stats, and a focused daily workflow.

## Default Habits

The app ships with nine starter habits that you can keep, edit, or delete:

| Emoji | Habit |
|-------|-------|
| 🌅 | Wake up at 05:00 |
| 💪 | Gym |
| 📚 | Reading / Learning |
| 💰 | Budget Tracking |
| 🎯 | Project Work |
| 🚫 | No Alcohol |
| 🌿 | Social Media Detox |
| 📓 | Goal Journaling |
| 🚿 | Shower |

## Data Storage

Check-in data is stored in the browser's `sessionStorage`:

- Your data persists for the duration of the browser session.
- Closing the tab or window resets the data.
- No data is sent to a server.

Use **Export CSV** in the sidebar to save a permanent copy before closing.

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `t` | Go to Tracker |
| `h` | Go to Habits |
| `s` | Go to Streaks |
| `m` | Go to Heatmap |

## Tech Stack

| Piece | Detail |
|-------|--------|
| HTML / CSS / JS | Vanilla — no frameworks |
| Charts | [Chart.js 4.4.0](https://www.chartjs.org/) via CDN |
| Fonts | [Inter](https://fonts.google.com/specimen/Inter) & [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts |
| Storage | `sessionStorage` (browser-native) |

## Browser Support

Any modern browser that supports CSS custom properties and ES6+ JavaScript — Chrome, Firefox, Safari, and Edge.

## License

This project is open source. Feel free to fork and customise it for your own use.
