# ElevateLabs Task 6 - Static Site on Github Pages

Simple static website (HTML, CSS, JS) that mimics a Netflix-style UI.
This repository contains the static files ready for local testing and GitHub Pages deployment.

---

## Project structure
```
index.html
styles.css
netflixstyles.css
scripts.js
README.md
```
<img width="1920" height="1080" alt="Screenshot from 2025-09-30 13-34-31" src="https://github.com/user-attachments/assets/dfeb5830-489d-4fed-8386-e9d0f103408e" />

---

## Quick preview
Open `index.html` in your browser (or run a local server) to preview the site.

### Output
<img width="1920" height="1080" alt="Screenshot from 2025-09-30 15-24-00" src="https://github.com/user-attachments/assets/9ed58564-f63a-4330-86fb-70dc1169f42a" />

---

## Prerequisites
- Git installed (`git` command).
- GitHub account to deploy via GitHub Pages.

---

## Deploy to GitHub Pages - step-by-step

### A. Create the GitHub repository (web UI)
1. On GitHub, click **New repository**.  
2. Name it (e.g. `Task6-ElevateLabs` or `shikharshukla.github.io` if you want to serve from the username root).  
3. Make it **Public** and click **Create repository**.

### B. Push your local project (command-line)
From your project directory:
```bash
git init
git add .
git commit -m "Initial commit: Netflix clone for Task 6"
# replace USERNAME and REPO with your GitHub username and repo name
git remote add origin https://github.com/USERNAME/REPO.git
git branch -M main
git push -u origin main
```

### C. Enable GitHub Pages
1. On GitHub, go to your repo → **Settings** → **Pages** (left sidebar).  
2. Under **Build and deployment**, choose **Branch: `main`** and folder **/** (root).  
3. Save. GitHub will show the published URL 

>Link: ```https://shikhrshukla.github.io/Task6-ElevateLabss/```

#### Output
<img width="1920" height="1080" alt="Screenshot from 2025-09-30 13-23-16" src="https://github.com/user-attachments/assets/9f809f71-8c4c-45a7-8848-8cae6a26308d" />
<img width="1920" height="1080" alt="Screenshot from 2025-09-30 15-02-46" src="https://github.com/user-attachments/assets/b812122c-04bd-480c-b3c4-a63c0cf946b1" />

---

## Troubleshooting
- **404 or blank page:** Ensure `index.html` is at the repository root for the branch you selected in Pages.
- **CSS/JS not loading:** Check relative paths and case sensitivity (file names are case-sensitive on GitHub Pages). 
- **Still not reflecting changes:** Make a small change (add a comment), commit & push to force Pages to rebuild, then wait a minute and refresh.

---

## Useful git commands summary
```bash
# create repo locally and push
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin <repo link>
git push -u origin main
```

---
