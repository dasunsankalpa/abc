# Publish this video on GitHub Pages

This folder is ready for GitHub Pages hosting.

## 1) Create a GitHub repository
- Go to GitHub and create a new repository (public is easiest for Pages).
- Keep it empty (no README/license/gitignore) if possible.

## 2) Push this folder from VS Code terminal
Run these commands in this folder:

```bash
git init
git add .
git commit -m "Add video site"
git branch -M main
git remote add origin https://github.com/<YOUR_USERNAME>/<YOUR_REPO>.git
git push -u origin main
```

## 3) Turn on GitHub Pages
- Open repository on GitHub.
- Go to **Settings → Pages**.
- Under **Build and deployment**:
  - Source: **Deploy from a branch**
  - Branch: **main**
  - Folder: **/ (root)**
- Save.

## 4) Open your live video URL
After 1–2 minutes:

`https://<YOUR_USERNAME>.github.io/<YOUR_REPO>/`

The page plays `Untitled Project.mp4` via `index.html`.
