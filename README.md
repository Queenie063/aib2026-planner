# AIB 2026 Personal Planner

A static web app built from the AIB 2026 conference program. It helps attendees browse the program, select sessions and papers, detect schedule conflicts, and export a personal plan.

## Features

- Filter by date, track, room, time, and session type
- Select full sessions
- Select individual papers and show their parent session
- Highlight sessions that contain selected papers
- Detect time conflicts automatically
- Export a personal plan to Excel and print-friendly PDF

## Files

- `index.html`: GitHub Pages entry page
- `conference-planner.html`: main application page
- `planner-data.js`: parsed conference data

## Notes

- Selections are stored only in each user's local browser storage and are not shared automatically with other users.
- This is a fully static site and is well suited for deployment with GitHub Pages.
