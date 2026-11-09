# CoverBar website

The built website for CoverBar, published at https://amrtnl.github.io/coverbar.
The marketing homepage is an AppView build. These three pages are plain HTML and are the ones to edit:

- `buy.html` — purchase page. Paste a Polar checkout URL, and later a real disk-image URL, into the JSON block at the top. Empty means the button is not shown.
- `activate.html` — paste a license key to open CoverBar. It does not look the key up.
- `admin.html` — tells you keys are managed in Polar. There is no login.

Do not point `downloadUrl` at anything except the notarized `CoverBar.dmg` once that file is on a release. Rebuilding the AppView site overwrites these pages unless that project is updated to match.
