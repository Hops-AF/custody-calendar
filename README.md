# Custody Calendar

A fully self-contained, single-file web app for tracking child custody schedules and generating custody reports.

## How it works

The entire application is a single HTML file (`custody-calendar.html`). There is no server, no database, and no account required. Just open the file in any modern web browser and start entering data.

## ⚠️ Important: Export Before Refreshing

**All data exists only in your current browser session.** There is no auto-save, no cloud sync, and no local storage persistence. If you:

- Refresh the page
- Close the tab or browser
- Navigate away

**All entered data will be permanently lost.**

Always use the **Export** button to download your data as an Excel file before closing or refreshing. Treat the export file as your save file — reload it or keep it as your record.

## Features

- Configure multiple parents and children
- Enter custody date ranges with a date picker
- Track which children are present for each period
- Add notes to entries
- Reporting window analysis (custom date range, by quarter, or presets like year-to-date)
- Per-child custody night breakdowns and percentages
- Export to Excel (.xlsx) with full entry data and summary

## Usage

1. Open `custody-calendar.html` in a web browser
2. Add parents and children in the **Configuration** section
3. Enter custody date ranges in the table below
4. Use the **Reporting** section to analyze custody distribution over a date range
5. Click **Export to Excel** to save your data before closing or refreshing

## Requirements

An internet connection is required on first load to fetch dependencies (React, Tailwind CSS, and the xlsx library via CDN). Once the page is loaded, no further connection is needed.
