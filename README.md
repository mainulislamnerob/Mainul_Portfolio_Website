# CSE Intern Portfolio — Md. Mainul Islam Nerob

A clean, HR-friendly single-page portfolio built with **HTML + TailwindCSS + JavaScript**. It automatically loads your public GitHub repositories and highlights featured projects.

## 🚀 Quick Start

1. Put your **profile photo** at `assets/profile.jpg` (square image recommended).
2. (Optional) Add `resume.pdf` in the project root to enable the **Download Resume** button.
3. Open `index.html` in a browser to preview.

## 🌐 Deploy to GitHub Pages

1. Create a new repository named e.g. `nerob-portfolio`.
2. Upload all files from this folder (or push via git).
3. Go to **Settings ➜ Pages** and set:
   - Source: **Deploy from a branch**
   - Branch: **main** / **master** and **/root**.
4. Wait for the green check, then visit the URL shown (e.g., `https://<your-username>.github.io/nerob-portfolio`).

## ⚙️ Customize

- Change colors/brand in the inline Tailwind config (in the `<head>`).
- Update text content in the **About, Education, Activities** sections.
- **Featured Projects:** edit the two cards under `#featuredProjects`.
- GitHub repos auto-load from the username `mainulislamnerob`. Change `GH_USER` in the script to use a different username.

## 🧩 Notes

- This project uses the Tailwind CDN for simplicity. For large sites, consider a build step.
- GitHub API is rate-limited for unauthenticated users (60 requests/hour). That’s sufficient for this page.
