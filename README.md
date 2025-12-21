# Vector Viewer Legal Pages

This repository contains the Terms of Use page for the Vector Viewer mobile application.

## Structure

- `index.html` - Main Terms of Use page
- `.nojekyll` - Tells GitHub Pages to serve files as-is without Jekyll processing
- `.github/workflows/deploy.yml` - GitHub Actions workflow for static deployment

## Deployment

This site is configured for GitHub Pages with automatic deployment via GitHub Actions. The workflow deploys static files without using Jekyll processing.

### GitHub Pages URL

- **Public repository**: `https://[username].github.io/vector-viewer-legal/`
- **Private repository**: `https://[username].github.io/[repository-name]/`

### App Store Connect Usage

Use the GitHub Pages URL in App Store Connect for the Terms of Use link.

## Setup Instructions

1. Push this repository to GitHub
2. Enable GitHub Pages in repository settings:
   - Go to Settings → Pages
   - Select "GitHub Actions" as the source
   - Save
3. The site will be automatically deployed when pushing to the main branch
4. The deployment workflow will run automatically and deploy the static files

### Workflow Features

- **No Jekyll processing**: Uses `.nojekyll` file and custom workflow
- **Static deployment**: Direct file serving without build process
- **Automatic deployment**: Triggers on push to main branch
- **Fast deployment**: No build steps required

## Features

- Responsive design that works on all devices
- Clean, professional styling
- Automatically displays current date as "Last Updated"
- No dependencies or build process required
- Works with GitHub Pages out of the box
