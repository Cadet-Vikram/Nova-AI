# NOVA Website

Landing page for the NOVA offline AI assistant.

## Deploy to GitHub Pages

1. Create a new GitHub repo called `nova-ai`
2. Upload all files in this folder to the repo root
3. Go to repo Settings → Pages → Source → Deploy from branch → `main` → `/ (root)`
4. Your site will be live at `https://YOUR_USERNAME.github.io/nova-ai`

## Update the download link

In `index.html`, replace this URL:
```
https://github.com/YOUR_USERNAME/nova-ai/releases/latest/download/AI.Assistant.Setup.exe
```
with your actual GitHub username.

## Host the installer on GitHub Releases

1. Go to your repo → Releases → Create a new release
2. Tag: `v1.0.0`
3. Upload `AI Assistant Setup.exe` as a release asset
4. The download link will then work automatically
