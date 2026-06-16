# AIB 2026 Conference Planner

A static personal planner for the Academy of International Business 2026 Annual Meeting in Manchester, a major annual conference for international business scholars and practitioners.

- Official conference website: <https://www.aib.world/events/2026-annual-meeting/>
- Planner website: <https://queenie063.github.io/aib2026-planner/conference-planner.html>

## Features

- Browse the AIB 2026 conference program as searchable and filterable cards.
- Filter by date, track, room, time, and session type.
- Select full sessions or individual papers.
- Show selected papers together with their parent session.
- Highlight sessions that contain selected papers.
- Detect schedule conflicts automatically.
- Export a personal conference plan to Excel.
- Generate a print-friendly PDF view.

## Files

- `index.html` - GitHub Pages entry page that redirects to the planner.
- `conference-planner.html` - main planner application.
- `planner-data.js` - parsed static conference program data.
- `.nojekyll` - keeps GitHub Pages from processing the static files with Jekyll.

## Notes

- This is a fully static site and is suitable for GitHub Pages.
- Selections are stored only in each user's browser local storage and are not synced across devices.
- The planner is an independent convenience tool built from the conference program data; the official AIB website remains the authoritative source for program updates.
