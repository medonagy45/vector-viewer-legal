# Vector Viewer Legal Pages

This repository contains legal pages for Vector Viewer app, hosted via GitHub Pages.

## Pages

- [Terms of Use](./terms-of-use.html)
- [Privacy Policy](https://www.iubenda.com/privacy-policy/52115918) (hosted on iubenda)

## GitHub Pages Setup

These pages are configured for deployment via GitHub Pages. **Works with both public and private repositories**.

### For Public Repositories:
The main domain will be:
`https://[username].github.io/vector-viewer/legal/`

### For Private Repositories:
GitHub Pages still works! The domain will be:
`https://[username].github.io/[repository-name]/legal/`

Replace `[username]` with your GitHub username and `[repository-name]` with your repository name.

## App Store Connect Links

Use these URLs in App Store Connect:

- **Privacy Policy**: `https://www.iubenda.com/privacy-policy/52115918`
- **Terms of Use**: `https://[username].github.io/[repository-name]/legal/terms-of-use.html`

## Deployment Instructions

### Step 1: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** section
4. Under "Build and deployment", select:
   - **Source**: Deploy from a branch
   - **Branch**: `gh-pages` 
   OR select **Source**: Deploy from a folder
   - **Folder**: `/docs` (root directory)
5. Click **Save**

### Step 2: Automatic Deployment
- GitHub Pages will automatically deploy and host your content
- Works for both public and private repositories
- Private repos include the repository name in the URL

### Step 3: Verify Deployment
- Visit your GitHub Pages URL to confirm it's working
- Check both Terms of Use and Privacy Policy links are accessible
- Your URL format will be:
  - Public: `https://[username].github.io/vector-viewer/legal/terms-of-use.html`
  - Private: `https://[username].github.io/[repository-name]/legal/terms-of-use.html`

## Important Notes

- **No code changes needed** - This is just hosting static HTML files
- **Free hosting** - GitHub Pages is free and reliable
- **SSL included** - All GitHub Pages sites automatically use HTTPS
- **Custom domain** - You can add a custom domain later if needed