# Chewy's Health Map

A visual health tracking application for Chewy.

## Description

This project is a static website that displays Chewy's health information in an interactive map format.

## Deployment

This site is automatically deployed to GitHub Pages using GitHub Actions.

### First-Time Setup

To enable GitHub Pages for this repository:
1. Go to the repository Settings
2. Navigate to "Pages" in the sidebar
3. Under "Build and deployment":
   - Source: Select "GitHub Actions"
4. Save the settings

### Automatic Deployment

Once GitHub Pages is enabled, the site deploys automatically when changes are pushed to the `alex's-branch` branch.

### Manual Deployment

You can also trigger a manual deployment:
1. Go to the Actions tab in the GitHub repository
2. Select the "Deploy to GitHub Pages" workflow
3. Click "Run workflow"

## Files

- `index.html` - Main HTML file with embedded CSS and JavaScript
- `chewy.jpg` - Image file used in the application
- `.github/workflows/deploy.yml` - GitHub Actions workflow for automatic deployment

## Viewing the Site

Once deployed, the site will be available at: `https://alexsfaulkner.github.io/Chewy/`

## Local Development

To view the site locally:
1. Clone the repository
2. Open `index.html` in a web browser

No build process is required as this is a static HTML site.
