# HabitLoop

HabitLoop is a personal habit tracker that makes daily progress visible. It starts with a blank habit list, so you can build a routine that fits your own goal.

## Features

- First-run setup for your name and main goal, with an optional first habit.
- Today, Month, and Year views with daily ticks, streaks, completion rates, SVG consistency rings, and a daily run-rate chart.
- Add, edit, and delete habits with emoji; browse months and keep future dates locked.
- 16 switchable themes across IPL (10 team-color palettes) and Anime (6 inspired-by palettes) collections.
- Export PDF and CSV, back up or restore JSON, edit your profile, and reset everything when needed.

## Use it

Download `HabitLoop.html` and open it in a modern browser. No installation or account is needed. Complete the short welcome flow, then add habits and tick them as you go. Use Settings to change themes or your profile. Keep a JSON backup if you need to move your data to another browser. Optionally use your browser's **Install app** or **Add to Home Screen** option if it offers one for the page; availability depends on the browser and how the HTML file is opened.

## Privacy and technology

Habit and profile data stays in your browser's local storage. There is no account, server sync, or analytics, and clearing browser data can erase your progress. A restore replaces the current data after confirmation. The app is one self-contained HTML file with no build step. PDF export loads `html2pdf.js` from the cdnjs CDN; when it is blocked or unavailable, the app opens the browser's print dialog instead. All other tracker features run locally.

Created by Akash Maurya
