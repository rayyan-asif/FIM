# File Integrity Monitor
This is a lightweight File Integrity Monitor (FIM) written in Python. It calculates SHA-512 hashes for files in a specified directory, creates a baseline for monitoring, and continuously checks for any changes, creations, or deletions of files. When an alert is triggered, a popup message box is displayed to notify the user.

---

## Features
* *SHA-512 Hashing*: Uses SHA-512 to ensure the integrity of the monitored files.
* *Baseline Creation*: Create a new baseline for the files in the specified directory.
* *Continuous Monitoring*: Continuously monitors the files against the saved baseline.
* *Popup Alerts*: Displays popup alerts using Tkinter for any file changes, creations, or deletions.
