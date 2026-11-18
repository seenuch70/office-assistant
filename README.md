# Office Assistant

A single-page office admin app: dashboard, vendors, stationery stock and orders, pantry and beverage orders, visitor gifts. Excel export on every table.

No build step and no server. Everything is in `index.html`.

## Run locally

Open `index.html` in Chrome, Edge or Firefox. It works offline.

## Publish on GitHub Pages

1. Create a new repository on GitHub (for example `office-assistant`).
2. Upload `index.html`, `.nojekyll` and `README.md` to the main branch.
3. Go to **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/ (root)**, then Save.
5. After a minute the app is live at `https://<your-username>.github.io/<repo-name>/`.

## Data

Entries are stored in each person's own browser (localStorage), not on GitHub. Use the Download Excel buttons to keep backups.
