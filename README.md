# HabitForge — Daily Habit Tracker

A lightweight, single-file habit tracker that runs entirely in your browser — no installation, no server, no account required.

## Overview

HabitForge helps you build and maintain daily habits by giving you a clear visual calendar, streak counters, a year-long heatmap, and quick CSV export. Everything runs from a single `habit-tracker.html` file.

## Features

- **Monthly tracker grid** — check off each habit for every day of the month; navigate between months with the arrow controls
- **Stats dashboard** — at-a-glance cards showing today's completion rate, current streak, best streak, and monthly completion percentage
- **Progress chart** — a 30-day bar chart (powered by [Chart.js](https://www.chartjs.org/)) showing daily completion percentages
- **Streaks page** — individual streak cards for every habit with a dot-grid showing the last 21 days
- **Year heatmap** — GitHub-style activity grid covering the full calendar year
- **Habit management** — add, edit, and delete habits; pick from 25 built-in emojis per habit
- **CSV export** — download all check-in data as a CSV file for use in spreadsheets
- **Dark / light theme** — toggle between themes; defaults to dark
- **Responsive layout** — collapsible sidebar works on mobile and desktop
- **Confetti & toasts** — celebratory animation when you complete all habits for the day

## Usage

1. Download or clone this repository.
2. Open `habit-tracker.html` in any modern web browser.
3. Start checking off your habits — no build step or internet connection required (fonts and Chart.js are loaded from CDNs on first open).

That's it. There is nothing to install.

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

Check-in data is stored in the browser's `sessionStorage`. This means:

- Your data persists for the duration of the browser session.
- Closing the tab or window will reset the data.
- No data is ever sent to a server.

Use the **Export CSV** option in the sidebar to save a permanent copy of your data before closing.

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
