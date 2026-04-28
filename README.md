# Library Shelf Navigation Assistant

Web-based tool for library staff to quickly locate books on shelves using Library of Congress call numbers.

## What It Does

Staff enters current location + call number → system returns correct floor, shelf, and directions.

## Tech

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python (Flask)
- **Database:** SQLite

## Setup

1. Clone repo and install Flask
2. Import Sierra data (CSV with call numbers + locations)
3. Run `python app.py`
4. Access via browser

## Data Needed

CSV from Sierra with:
- Call number
- Location (floor/shelf)
