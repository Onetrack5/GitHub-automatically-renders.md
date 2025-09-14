# GitHub-automatically-renders.md

Alright One — here’s a polished README draft you can drop straight into your GitHub repo alongside the script.
It’s written to be clear for first‑time users, but still detailed enough for power users who want to know exactly what they’re getting.

DeepCleanup Advanced UI v1.1.0
Safe‑by‑default, glassy Windows cleanup tool with profiles, settings persistence, and optional deep repair.
Built for both quick tidying and full‑service maintenance.

✨ Features
- Modern UI
- Acrylic/glassy blur background
- Dark/Light mode toggle
- High‑contrast mode for accessibility
- Adjustable font size
- Tooltips for all controls
- Two Modes
- Quick Cleanup — safe, fast steps only
- Deep Maintenance — all steps, including optional deep repair (DISM/SFC)
- Cleanup Steps (21 total)
- DNS/Winsock/TCP resets
- Temp/cache clearing (system, browser, update)
- Disk cleanup & drive optimization
- Privacy traces cleanup
- Startup apps listing
- Optional deep repair: DISM and SFC (unchecked by default)
- Recycle Bin, Prefetch, Thumbnail cache, WER reports
- User profile temp cleanup
- Optional bloatware removal
- Profiles & Settings
- Save/load step selections as named profiles
- Remembers theme, font, contrast, window size/position, selected steps, log path
- Logging & Summary
- Color‑coded log (green=OK, yellow=skipped, red=error)
- Save log to file
- Post‑execution summary: disk space before/after, freed space, time taken
- Buttons to open log, run again, or exit
- Safety
- Risky steps unchecked by default
- Confirmation prompts for destructive actions
- Cancel button stops mid‑run gracefully
- System restore point creation before cleanup

📸 UI Overview

<img width="862" height="701" alt="image" src="https://github.com/user-attachments/assets/aa6cee15-02c1-4a5f-a420-6f104469abf6" />

🚀 Usage
- Run as Administrator
Many steps (restore point, DISM/SFC, service stops, bloatware removal) require elevation.
- Choose a Mode
- Click Quick Cleanup for safe, fast steps.
- Click Deep Maintenance for all steps, including deep repair.
- Adjust Selections
Manually check/uncheck any steps.
- Start Cleanup
- Press Start or hit Alt+S.
- Watch the log for progress.
- Cancel anytime with Cancel.
- Review Summary
See freed space, time taken, and open the log.

⚠️ Notes
- DISM/SFC are long‑running repairs (10–40+ minutes) and require internet for DISM.
They are unchecked by default — enable only when needed.
- First run creates %APPDATA%\DeepCleanup for settings and profiles.
- If the window opens off‑screen (multi‑monitor change), delete settings.json in %APPDATA%\DeepCleanup.
