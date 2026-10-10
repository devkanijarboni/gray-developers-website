# Gray Developers — ULTIMA AI Beta V1

A lightweight static website built with HTML, CSS and vanilla JavaScript. It has no server-side code, external dependencies, AI connection, API keys, authentication, payments or database.

## Project files

- index.html — website page, in the repository root
- styles.css — responsive monochrome design
- script.js — mobile navigation, current year and scroll reveal
- assets/gray-developers-logo.png — full supplied Gray Developers logo
- assets/favicon.png — small tab icon derived from the logo

## Preview on your computer

1. Open PowerShell or a terminal.
2. Change to the project folder:
   cd "C:\Users\User\OneDrive\Documents\ChatGPT\ULTIMA AI"
3. Start a local static server:
   python -m http.server 8000
4. Open http://localhost:8000 in your browser.
5. Stop the server with Ctrl+C.

## Publish for free with GitHub Pages

This site is already arranged for a project site: index.html is in the repository root and the CSS, JavaScript, logo and favicon use relative paths. No build step or paid service is needed. For GitHub Free, use a public repository. GitHub Pages sites are public on the internet.

### 1. Create a repository

1. Sign in at [github.com](https://github.com/).
2. Select the + menu in the upper-right corner, then choose New repository.
3. Name it something like gray-developers-website.
4. Select Public.
5. Leave Add a README file unchecked because this project already has one.
6. Select Create repository.

### 2. Upload the website files

1. On the new repository page, choose Add file → Upload files.
2. Upload these files and the assets folder from this project:
   - index.html
   - styles.css
   - script.js
   - README.md
   - assets/gray-developers-logo.png
   - assets/favicon.png
3. Confirm the upload list keeps the images under the assets/ folder.
4. Enter a commit message such as Add Gray Developers website.
5. Choose Commit changes to the main branch.

You can upload the folder and files from your computer using GitHub's browser upload page. If you prefer GitHub Desktop or Git, publish the same project folder and preserve the assets/ directory structure.

### 3. Turn on GitHub Pages

1. In the repository, open Settings.
2. In the left sidebar, choose Pages.
3. Under Build and deployment, set Source to Deploy from a branch.
4. Set Branch to main and the folder to /(root).
5. Choose Save.
6. Wait for the Pages deployment to finish. You can follow it in the repository's Actions tab or return to Settings → Pages.

### 4. Open your Pages address

For a repository named gray-developers-website, the address will follow this pattern:

    https://YOUR-GITHUB-USERNAME.github.io/gray-developers-website/

Replace YOUR-GITHUB-USERNAME with your GitHub username. The actual site is ready only after GitHub reports a successful deployment and that address loads publicly.

If you instead name the repository YOUR-GITHUB-USERNAME.github.io, GitHub uses the account's root Pages address:

    https://YOUR-GITHUB-USERNAME.github.io/

More help: [GitHub Pages quickstart](https://docs.github.com/en/pages/quickstart), [publishing from a branch](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site), and [uploading files](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository).

## Product status

Object creation assistance, environment and place building assistance, and Roblox Luau coding assistance are intended capabilities with implementation status marked unverified. The workflow is conceptual. The website does not connect to an AI model.

Keep a future ULTIMA AI application separate from this static marketing site. Add a real model connection only in that future application phase.