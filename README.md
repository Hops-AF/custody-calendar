# Custody Calendar

A fully self-contained, single-file web app for tracking child custody schedules and generating custody reports.

## How it works

The entire application is a single HTML file (`custody-calendar.html`). There is no server, no database, and no account required. Just open the file in any modern web browser and start entering data.

## Local saving and backups

The app automatically saves data to local browser storage on the current device. Refreshing or reopening the page in the same browser restores the household, entries, schedules, colors, and reporting preferences.

There is no cloud account or cross-device sync. Browser data can still be cleared by browser settings, private-browsing behavior, or device maintenance, so export an Excel or CSV backup periodically.

**All entered data will be permanently lost.**

Always use the **Export** button to download your data as an Excel file before closing or refreshing. Treat the export file as your save file — reload it or keep it as your record.

## Features

- Guided setup for parents, children, and per-child schedules
- Editable recurring schedules: EOW, EOW + midweek, alternating weeks, and 2-2-3
- Configure multiple parents and children with custom colors
- Color-coded calendar with child filters, split sibling schedules, and cross-month selection
- Enter custody date ranges with a date picker
- Track which children are present for each period
- Add notes to entries
- Reporting window analysis (custom date range, by quarter, or presets like year-to-date)
- Per-child custody-day breakdowns and percentages
- Export to Excel (.xlsx) or CSV with full entry data and summary

## Usage

1. Open `custody-calendar.html` in a web browser
2. Complete the guided household setup
3. Use the calendar to select a start and end date, then assign a parent
4. Use the child filter to inspect different sibling schedules
5. Use **Reporting** to analyze custody distribution over a date range
6. Export an Excel or CSV backup periodically

## Requirements

An internet connection is required on first load to fetch dependencies (React, Tailwind CSS, and the xlsx library via CDN). Once the page is loaded, no further connection is needed.
