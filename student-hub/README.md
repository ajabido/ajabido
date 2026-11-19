# Student Hub (demo)

**Live demo:** https://ajabido.github.io/ajabido/student-hub/

All students in this demo are invented. Names, emails and phone numbers are made up, and the dive center, "BlueReef Dive Center", is fictional.

## Problem
A dive center's certification history sits in many spreadsheets, spread over years. The same diver appears several times, with different spellings and missing dates. The call center can't tell who finished Open Water and is ready to be offered the next course.

## What I built
A single-page database for finding former students and following up with them:
- Search and filter by certification level, year, country, trust status and contact activity
- A "next step" suggestion for every diver (for example, Open Water, then Advanced, then Rescue)
- Possible-duplicate detection (same phone number, different record)
- A verification queue, so only checked contacts reach a call list
- Live entry of new students with the staff member's name attached, plus contacted/not-contacted tracking
- Monthly, yearly and per-course reports, and CSV / call-list export

## Result
A working prototype built from two years-long spreadsheet archives, replacing manual searching. The demo here runs on sample data only.

## Built with
Plain HTML, CSS and JavaScript in one file. In this demo, changes are saved in your browser only.
