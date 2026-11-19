# DiveDesk Ops

**Live demo:** open `index.html`. All boats, staff, guests and dive sites in the demo are fictional.

**The problem.** A dive center and its head office planned each day's boat trips in a shared spreadsheet that was emailed back and forth. Versions got mixed up, nobody could see at a glance which boats were full or short of crew, and manifests and kit lists were typed up by hand every morning.

**What I built.** A browser-based operations board for a dive center:
- **Day board:** every boat trip as a card with guests vs seats, crew and live warnings (over capacity, no captain, staff on two boats or on leave, missing ID copies or forms).
- **What to prepare:** tanks, BCDs, wetsuits, boots, fins and lunches counted automatically from the bookings and checked against stock.
- **Bookings, staff roster and equipment:** guest search and filters, a weekly roster with leave, and stock with service-due alerts.
- **Print and export:** boat manifest and day plan on A4, plus CSV export.
- **Handover:** the two locations swap a small file instead of the whole spreadsheet. The app previews what is new, changed or deleted before merging, and the newest edit wins.

**The result.** A working prototype that turns the morning planning into one screen, with problems flagged before the boats leave. It works offline in one HTML file and runs on a computer or an iPad.

**Built with.** HTML, CSS and JavaScript (no frameworks, no server), browser storage with JSON backups, AI-assisted development.
