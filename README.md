# Watfa — Personal Workspace

Watfa is a lightweight, responsive workspace for organizing tools, notes, projects, resources, and ideas. The website lives in [`index.html`](./index.html) and requires no build tools or dependencies.

## Open the website

- **Repository:** https://github.com/yazoniplay/watfa-structure-
- **Website file:** https://github.com/yazoniplay/watfa-structure-/blob/main/index.html

### Publish with GitHub Pages

1. Open this repository's **Settings → Pages**.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Choose branch **main** and folder **/(root)**, then save.
4. After GitHub finishes publishing, open the website URL shown in the Pages settings. It will usually be `https://yazoniplay.github.io/watfa-structure-/`.

## Features

- Dashboard with entry counts and recent activity.
- Separate views for tools, notes, projects, resources, and ideas.
- Add, edit, delete, and search entries.
- Tool details include category, website, pricing, and description.
- Light and dark themes; responsive layout for phones and desktops.
- No external libraries, backend, or build process required.

## Important data note

Entries are stored in the browser's `localStorage` on the device where they are added. They are **not automatically synced** across devices or users, and clearing browser site data can remove them. This version has no account system or cloud database. Do not store passwords, API keys, access tokens, or other secrets in it.

## Optional Markdown blueprint

The `tools/`, `notes/`, `projects/`, `resources/`, and `ideas/` folders also contain reusable Markdown templates for keeping records in files instead of the browser.
