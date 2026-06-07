# LocalArea — Independent Shops & Restaurants

A simple web application to find independent shops and restaurants in your local area.

## Hosting on GitHub Pages

This project is ready to be hosted on GitHub Pages. You can choose one of the following two methods:

### Method 1: Deploy from a Branch (Standard)

1. Go to your repository on GitHub.
2. Click on **Settings** > **Pages**.
3. Under **Build and deployment** > **Source**, select **Deploy from a branch**.
4. Choose the `main` branch and the `/ (root)` folder.
5. Click **Save**.

### Method 2: Deploy via GitHub Actions (Recommended)

This repository includes a GitHub Action workflow that automatically deploys the site whenever you push changes to the `main` branch.

1. Go to your repository on GitHub.
2. Click on **Settings** > **Pages**.
3. Under **Build and deployment** > **Source**, select **GitHub Actions**.
4. The workflow in `.github/workflows/deploy.yml` will handle the rest.

## Local Development

Simply open `index.html` in your browser, or use a local server like `Live Server` in VS Code.
