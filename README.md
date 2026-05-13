GitHub Repo Selector v1.0

A modern Elementor-powered GitHub repository showcase plugin for WordPress.

GitHub Repo Selector allows WordPress websites to connect directly to GitHub repositories using a secure GitHub Personal Access Token system. The plugin was designed to make showcasing repositories, plugins, web apps, and development projects simple inside Elementor without requiring custom code or manual shortcode setup.

The plugin dynamically pulls repositories from the connected GitHub account and provides live repository previews, branch switching, README rendering, GitHub buttons, and ZIP downloads directly from the Elementor editor.

⸻

Features

GitHub Account Integration

Connect a GitHub account using a GitHub Personal Access Token and automatically pull repositories connected to the authenticated GitHub account.

⸻

Elementor Live Rendering

Live Elementor rendering updates instantly while editing:

* Repository selections
* Display modes
* Branch selections
* README visibility
* Button visibility
* Styling controls

No manual page refresh required.

⸻

Display Modes

Supports:

* Single repository mode
* Multiple repository mode
* All repositories mode

⸻

Branch-Aware Repository System

Repositories can display:

* Main/default branch
* Custom selected branch

GitHub links, README previews, and ZIP downloads automatically follow the selected branch.

⸻

View on GitHub Button

Automatically generates GitHub repository links matching the selected repository and branch.

Example: https://github.com/USERNAME/REPOSITORY/tree/BRANCH

Download ZIP Button

Creates direct GitHub ZIP download links for:

* Entire repository
* Selected branch ZIP
Example: https://github.com/USERNAME/REPOSITORY/archive/refs/heads/BRANCH.zip
README Preview Support

Display GitHub README files directly inside Elementor layouts.

⸻

Repository Cache System

The plugin includes a repository caching system designed to:

* Reduce GitHub API calls
* Improve Elementor dropdown performance
* Speed up repository loading
* Store repository lists locally inside WordPress

⸻

Mobile-Friendly Elementor Controls

Optimised for:

* iPhone
* iPad
* Responsive Elementor editing
* Mobile dropdown rendering

⸻

GitHub Token Setup

This plugin requires a GitHub Personal Access Token.

Recommended token type: Fine-grained personal access token
Recommended permissions: Repository access: All repositories
Contents: Read-only
Metadata: Read-only
GitHub token settings: GitHub → Settings → Developer settings → Personal access tokens
How It Works

Step 1 — Connect GitHub

Add your GitHub Personal Access Token inside: WordPress Admin → GitHub Repo Selector Settings
Step 2 — Update Repository Cache Press: Update Repositories
The plugin will:

* Connect to GitHub
* Pull repositories
* Build the Elementor repository dropdown cache

⸻

Step 3 — Add Widget To Elementor

Inside Elementor:

1. Add the GitHub Repo Selector widget
2. Choose:
    * Single repository
    * Multiple repositories
    * All repositories
3. Select repository/branch
4. Enable README or buttons if required

⸻

Step 4 — Publish

The widget automatically renders:

* GitHub repository data
* README previews
* GitHub links
* ZIP downloads

⸻

Tech Stack

* WordPress
* Elementor
* PHP
* CSS
* JavaScript
* AJAX
* GitHub REST API
* Responsive Design
* WordPress Hooks & Actions

  Version v1.0
  Author

Connor Moizer
https://connormoizer.com

⸻

License

GPL-2.0-or-later
