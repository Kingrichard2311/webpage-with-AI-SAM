# Richard Lamy — Cybersecurity Apprentice (Personal Portfolio)

**Short description**  
This repository contains the source for *Richard Lamy — Cybersecurity Apprentice*, a personal portfolio site and a set of small, educational security projects (Password Strength Checker, Phishing Awareness module, Encryption demos). The site is intended for learning and demonstration purposes.

---

## Contents / Quick links
- `index.html` (or `Richard Lamy _ Cybersecurity Apprentice.html`) — main portfolio page  
- `code cracker.html` — Password Strength Checker (Matrix-themed)  
- `phishing awerness.html` — Phishing Awareness interactive training  
- `ocean encryption tool.html` — Encryption demos (Caesar, ROT13, Base64, AES examples)  
- `IMG_4558.png` — portrait used on the homepage  
- `assets/` — optional folder for images, thumbnails and extra files

> Tip: filenames with spaces can cause URL encoding issues (`%20`). For easier hosting and linking, consider renaming files to URL-friendly names like `code-cracker.html` and `phishing-awareness.html`.

---

## Features
- Responsive single-page portfolio: **Home**, **Ambitions**, **Technical Skills**, **Projects**, **Contact**.  
- Interactive project viewer (modal + iframe) for previewing local project HTML files or embedded YouTube content.  
- Client-side, offline-capable demo projects for teaching basic cyber hygiene and security concepts.  
- Clean, dark-themed design with animated background and interactive widgets.

---

## Demo / Purpose
- **Purpose:** Provide an accessible demonstration of practical cybersecurity learning tools and a personal portfolio.  
- **Audience:** Students, apprentices, tutors and anyone learning about password hygiene, phishing recognition and basic encryption.  
- **Estimated time:** 2–15 minutes depending on which project is used.

---

## Run locally (recommended)
Some browsers block certain iframe/JS behaviours when pages are opened using `file://`. Serve the folder via a simple HTTP server for full functionality.

### Using Python (recommended)
```bash
# from repo root
python -m http.server 8000
# open http://localhost:8000/ in your browser
