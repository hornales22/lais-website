
# School Website Starter

A fast, accessible, mobile-friendly school website you can host anywhere (GitHub Pages, Netlify, or your school's server).

## Structure
- `index.html` — Home
- `about.html` — About, Vision & Mission
- `academics.html` — Curriculum & Clubs
- `admissions.html` — Requirements & Online Pre-Registration (mock submit)
- `news.html` — News (loaded from `/data/news.json`)
- `contact.html` — Contact information & form (mock submit)
- `css/styles.css`, `js/main.js` — Styles & behavior
- `data/` — Edit JSON files for announcements and news
- `assets/` — Logos and images

## Quick Start (Local)
1. Download and unzip this folder.
2. Open `index.html` in a browser.

## Deploy to GitHub Pages
1. Create a new public repository named `school-website`.
2. Upload this folder's content to the repo.
3. In **Settings → Pages**, set source to **main** branch (`/root`).
4. Wait a minute; your site will be live at `https://<your-username>.github.io/school-website/`.

## Deploy to Netlify
1. Drag-and-drop the folder into the Netlify dashboard (or connect your Git repo).
2. Netlify will provide a live URL instantly.

## Customize
- Replace `assets/icons/logo.svg` and `assets/images/campus.jpg` with your own.
- Edit text content in each HTML page.
- Update `/data/home.json` and `/data/news.json` for announcements/events/news.
- Colors: adjust CSS variables in `:root`.

## Accessibility & Performance
- Semantic HTML, skip link, focus outlines, proper landmarks.
- Responsive layout and accessible navigation.

## Notes
- Forms are demo-only (no backend). Connect to Google Forms or a service like Formspree for real submissions.
