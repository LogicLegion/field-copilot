# field-copilot
Voice field copilot
# 🎙️ Angela — Voice Field Copilot

A hands-free, GPS-aware voice assistant for field technicians. Load your daily kiosk CSV, and Angela reads out your next stop — address, distance, status, and commitment impact — while you drive.

**Live demo:** https://field-copilot-jpzm.onrender.com/angela.html

---

## What It Does

- **Reads stops out loud** — store name, full address, distance, status, reject %
- **Prioritizes by GPS** — won't send you 300 km away when there's real work nearby
- **Tracks commitment kiosks** — top 33% by volume, boosted when below 98% uptime
- **Works offline** — everything runs in the browser, no server, no database
- **Voice-driven** — hands-free commands for driving

---

## Voice Commands

| Command | What it does |
|---|---|
| "Angela, next stop" | Reads the next prioritized stop |
| "Angela, repeat" | Re-reads the current stop |
| "Angela, nearby" | 3 closest kiosks within 10 km |
| "Angela, mark done" | Mark current stop as visited |
| "Angela, skip" | Skip without marking done |
| "Angela, commitment status" | Progress on 98% uptime target |
| "Angela, commitment mode" | Restrict routing to commitment kiosks only |
| "Angela, exit commitment mode" | Back to all kiosks |
| "Angela, how many critical" | Fleet-wide critical count |
| "Angela, stop" | Pause listening |

---

## How Prioritization Works

Every stop is scored:

