# Career Growth & Leadership Tracker

A free, buildless personal career-development app for engineering leadership by 2029.

## Use
Open the GitHub Pages site. Start with the seven dashboard capabilities, record achievements in the monthly journal, set annual goals and write quarterly/annual reviews. Convert journal entries into editable STAR drafts; add your individual actions and verified results. Progress starts at zero and is self-assessed, not inferred from qualifications.

## Records and backups
All user-entered records are stored only in this browser's localStorage under `career-growth-leadership-v1`. They are not committed to GitHub or uploaded to a backend. Browser profiles, browsers and devices have separate data. Clearing site data removes records. Storage is limited by the browser; there is no artificial entry-count limit.

Download a full JSON backup weekly, keep copies outside the browser and restore through Backups & exports on another device. The app reminds you after seven days when opened; it cannot create unattended file backups. A backup download timestamp is not confirmation that the downloaded file has been kept safely. Restore validates the format and asks before replacement. Readable Markdown exports cover achievements, annual goals/reviews and interview stories.

The repository and site code are public. The motivation page contains the personal rationale requested by the owner; journal records remain local. Do not commit backup files or confidential employer information.

## GitHub Pages
Settings → Pages → Deploy from a branch → main → / (root) → Save. No dependencies, build step, subscription, analytics or paid backend.

## Local use
Serve this directory with a static web server, for example `python3 -m http.server 8000`. Relative asset paths support repository-subpath hosting.
