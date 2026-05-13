# Wordpress-Plugins

GitHub Repo Selector v1.0

A modern GitHub repository showcase and management plugin for WordPress and Elementor.

GitHub Repo Selector allows website owners, developers, and portfolio creators to connect their GitHub account directly to WordPress using a GitHub Personal Access Token and dynamically display repositories, branches, README content, GitHub statistics, download buttons, and front-end GitHub management tools.

The plugin was designed as a plug-and-play GitHub integration system with Elementor support, front-end dashboard controls, responsive layouts, and GitHub syncing features.

---

Features

GitHub Repository Display

- Display repositories directly from GitHub.
- Show repository descriptions, branches, stats, and README content.
- Automatically updates repository and branch caches from GitHub.
- Supports single repository mode, multi repository mode, and all repositories mode.

Branch Support

- Branch dropdown selector.
- View repositories by selected branch.
- Download ZIP files from selected branches.
- Open selected branches directly on GitHub.

README Integration

- Automatically pulls README.md content from GitHub.
- Supports:
  - README.md
  - readme.md
  - README
  - README.MD
  - Readme.md
- Scrollable README rendering.
- Front-end README editing support.
- README popup editor with markdown toolbar.

Front-End Dashboard Mode

Optional front-end GitHub management tools:

- Update repositories & branches cache.
- Create repositories.
- Create branches.
- Delete repositories.
- Delete branches.
- Delete files.
- Upload ZIP files directly to GitHub.
- Create or update custom files.
- Create and edit README.md files.

GitHub Management Tools

- Add repository or branch from one dashboard box.
- Repository dropdown automatically appears when adding a branch.
- File deletion dropdown loads GitHub files dynamically.
- Latest GitHub edit URL tracking.
- Automatically clears latest edit cache when deleted from GitHub.

Elementor Support

- Live Elementor rendering support.
- Responsive controls.
- Repository dropdown selectors inside Elementor editor.
- Front-end dashboard switch for management mode.

Download Buttons

Each repository card supports:

- View on GitHub button.
- Download ZIP button.
- Branch-aware downloads.

Responsive Layout

- Automatically adjusts columns depending on screen size.
- Mobile friendly layout.
- Dashboard cards styled consistently across devices.

---

GitHub Token Setup

This plugin requires a GitHub Personal Access Token.

Recommended token type:

- Classic Personal Access Token

Recommended permissions:

- repo
- workflow
- read:user

Create your token at:
https://github.com/settings/tokens

After creating the token:

1. Open GitHub Repo Selector Settings.
2. Paste the token into the token field.
3. Save changes.
4. Click "Update Repositories & Branches".

---

Front-End Dashboard Features

When Front-End Dashboard Mode is enabled:

- GitHub tools appear directly on the front-end.
- Repository and branch management becomes available.
- README editor popup becomes available.
- GitHub cache statistics are shown:
  - Repositories cached
  - Branches cached
  - Last updated
  - Latest GitHub edit URL

---

Included GitHub Tools

Add Repository or Branch

One combined dashboard tool for:

- Creating repositories.
- Creating branches linked to existing repositories.

Delete Repository / Branch / File

Single delete box supporting:

- Delete repository.
- Delete branch.
- Delete file.

README Popup Editor

- Load README directly from GitHub.
- Opens in popup editor.
- Markdown-style toolbar included.
- Scrollable editing area.

ZIP Uploads

Upload ZIP files directly to GitHub repositories and branches.

Custom File Creation

Create or update:

- README.md
- JSON files
- CSS files
- PHP files
- Markdown files
- Other custom files.

---

Tech Stack

- WordPress
- Elementor
- PHP
- JavaScript
- GitHub REST API
- AJAX
- Responsive CSS
- Markdown README Rendering

---

Author

Connor Moizer
https://ConnorMoizer.com

---

Version

v1.0