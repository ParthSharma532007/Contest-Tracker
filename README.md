# Contest Tracker — Simple

This is a minimal contest tracker inspired by the referenced GitHub project. It is purposefully small and easy to understand.

How to run:

```bash
npm install
npm run dev
```

Open the local URL shown (e.g. `http://localhost:5173` or `5174`).

Notes:
- The app fetches contest lists from `https://kontests.net/api/v1/all` and falls back to sample data when the API is unreachable.
- Click "Enable Notifications" and allow permission to get browser alerts before contests.
# Contest Tracker

A React + TypeScript website that lists upcoming coding contests and sends browser notifications before they begin.

## Features

- Fetches contest data from the public Kontests API
- Shows upcoming contests sorted by start time
- Filters contests by platform
- Lets you choose notification lead time in minutes
- Sends browser notifications for contests starting soon

## Run Locally

```bash
npm install
npm run dev
```

Then open the local URL shown in terminal (typically `http://localhost:5173`).

## Build for Production

```bash
npm run build
npm run preview
```

## Notification Notes

- Click **Enable Notifications** in the app.
- Keep the tab open to receive alerts.
- If notifications are blocked, allow them in browser site settings.
