Local development
=================

Open this repository folder in VS Code:
New folder

This is a standalone HTML dashboard. No npm install or build is needed.

On Windows with Python installed, double-click start.cmd.
Then open http://127.0.0.1:8000 in your browser.
Keep the server window open while working; press Ctrl+C to stop it.
Alternatively, open index.html directly.

Edit index.html and refresh the browser.
Use the same browser and address to retain browser-local edits.
Use the dashboard export/backup controls before changing browsers or addresses.

Git is already initialized and origin points to the original GitHub repository.
Run Git commands directly from "New folder", which is now the repository root.
Review changes: git status
Review file edits: git diff

Dashboard data and privacy
==========================

This standalone dashboard includes captured learner data and wellbeing case
history. Keep this repository PRIVATE: it contains identifiable learner
performance, wellbeing and safeguarding records. This package does not
configure GitHub Pages or publish the dashboard.

Browser-local changes (RAG categories, follow-up plans and gateway edits) are
saved only in the browser where you make them. Use the dashboard backup/export
controls to retain those changes. Existing browser edits are not embedded in
this source package.

Snapshots: performance and Aptem data 23 October 2026; wellbeing data and notes
26 October 2026. No live connection or automatic refresh is configured.

Files:
index.html - standalone dashboard
Wellbeing Follow-up Template.txt - editable follow-up format
README.txt - these instructions
start.cmd - local server launcher (requires Python)
.gitignore - excludes OS metadata and local logs
