# CORE — 24 Hour Tracker

A small, mobile-first hourly planner. Each of the 24 hours has exactly five core task slots.

## Features
- 24 hourly sections, with five editable task slots per hour
- Mark tasks as completed and see daily progress
- Choose dates; each day's plan is saved locally in the browser
- Focus-hour toggle for distraction-light planning
- Export a day as CSV
- Minimal three-color palette
- Offline cache/PWA support when served from HTTPS or localhost

## Quick start
Open `index.html` in a modern browser. Data is stored in that browser's local storage. The basic tracker works when opened directly as a file.

## Install as an app
For PWA installation/offline caching, serve the folder from `localhost` or an HTTPS host. For example, from this folder run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in a browser that supports PWA installation. On Android Chrome, use the browser menu and choose **Install app** or **Add to Home screen**.

## Privacy
No account or external service is used. Plans stay in the browser's local storage unless exported by the user. Clearing browser site data can remove saved plans.
