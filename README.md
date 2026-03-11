# Housekeeper Masterboard

This repo hosts the static dashboard for Mac's housekeeper agent. The generated `index.html` is the same file the cron job produces locally; publishing via GitHub Pages makes it easy to share status with stakeholders without terminal access.

## Local development

```bash
cp ../housekeeper_dashboard.html index.html
python3 -m http.server 8080
```

## Deployment

The `main` branch is published via GitHub Pages (branch source). Update the dashboard by replacing `index.html`, committing, and pushing to `main`.
