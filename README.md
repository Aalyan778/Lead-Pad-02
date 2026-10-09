# LeadPad

A single-file, offline lead tracker that runs in your browser. Paste leads, and LeadPad numbers them, detects duplicates (by phone, email, website/social link, or business name + address), and exports to Excel, Word, or text.

## Use it

- **Locally:** download `index.html` and double-click it. No install, no server, no internet needed.
- **Online (GitHub Pages):** in your repository go to **Settings → Pages → Build and deployment → Source: Deploy from a branch → `main` / `(root)`**. Your app will be live at `https://<your-username>.github.io/<repo-name>/`.

## Features

- Duplicate detection against a permanent record (stored in your browser's IndexedDB)
- Partial-duplicate merge (keeps only new info)
- Daily goal with celebration, stats, undo, search
- Auto-paste from clipboard, sound alerts
- Export: Excel (.xlsx), Word (.doc), .txt; backup/restore

## Privacy

All data stays in your browser (localStorage / IndexedDB). Nothing is uploaded anywhere.

## Note

The default ignore list in `index.html` contains `zooreach@zooreach.org` / `zooreach.org`. Edit the `IGN` variable or use the in-app **Ignore list** button if you don't want that in a public repo.
