# Daisy Huang Portfolio Website

A personal portfolio website sharing data science projects, blog posts, and interactive mini-apps. Built with **HTML, CSS, JavaScript, and PyScript (Python in the browser)**.

---

## Project Structure
```
portfolio-site/
├── index.html              # Homepage (About, Projects)
├── projects.html           # Projects listing page
├── blog.html               # Blog listing page
├── contact.html            # Contact page
├── puzzle.html             # Halloween puzzle (PyScript-powered)
├── style.css               # Shared stylesheet
├── math-tutor/
│   └── index.html          # Interactive multiplication practice app
├── posts/                  # Blog post pages
│   ├── drought-prediction-models.html
│   ├── snowborad_trip_data_viz.html
│   └── twitter-network-analysis.html
├── assets/                 # Images and other static assets
├── other_files/            # Miscellaneous files
├── CNAME                   # Custom domain config (GitHub Pages)
└── README.md
```

---

## How to Run Locally
1. Download or clone this repository.
2. Open `index.html` in your browser (double-click it).

No server setup required — everything is static HTML/CSS/JS/PyScript.

---

## How to Deploy on GitHub Pages
1. Create a new GitHub repository (e.g., `portfolio-site`).
2. Upload all files and folders.
3. Go to **Settings → Pages**.
   - Select `main` branch → root (`/`) folder.
   - Save.
4. After a minute, your site will be live at:
   ```
   https://<your-username>.github.io/portfolio-site/
   ```

To use a custom domain, update the `CNAME` file with your domain name.

---

## Features

### Math Tutor (`math-tutor/`)
An interactive multiplication practice app with:
- Number selector screen to choose which times tables to practice
- Quiz interface with spacebar shortcut to trigger microphone input
- Instant feedback on answers

### Halloween Puzzle (`puzzle.html`)
- PyScript-powered word unscramble puzzle
- Unscramble **NIKPUM** → correct answer: `PUMPKIN`
- Reveals party invitation details once solved

### Blog (`blog.html`, `posts/`)
- Data science write-ups covering topics like drought prediction models, snowboard trip data visualization, and Twitter network analysis

---

## Customization
- Update `index.html` with your own About and Projects info.
- Add new blog posts to `posts/` and link them from `blog.html`.
- Edit `math-tutor/index.html` to change quiz behavior.
- Adjust colors/fonts in `style.css`.

---

## License
Free for personal use.
