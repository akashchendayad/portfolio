# Akash R — Portfolio Website

Personal portfolio site for **Akash R**, Backend Developer (Node.js · PHP · TypeScript).

🌐 **Live site:** [your-netlify-url.netlify.app](https://your-netlify-url.netlify.app)

---

## 🚀 Deploy to Netlify

### Option 1 — Drag & Drop (fastest)
1. Go to [app.netlify.com](https://app.netlify.com)
2. Drag the entire project folder onto the Netlify dashboard
3. Done — your site is live instantly!

### Option 2 — Git + Netlify CI (recommended)
1. Push this repo to GitHub (see below)
2. In Netlify → **Add new site → Import an existing project**
3. Connect your GitHub account and select this repo
4. Build settings: leave blank (static site, no build command needed)
5. Click **Deploy** — every push to `main` auto-deploys

---

## 🐙 Git Setup

```bash
# 1. Initialise the repo
git init
git add .
git commit -m "initial: portfolio site"

# 2. Create a repo on GitHub (github.com → New repository)
#    Name it: portfolio  (or akash-portfolio)
#    Set it to Public or Private

# 3. Link and push
git remote add origin https://github.com/akashchendayad/portfolio.git
git branch -M main
git push -u origin main
```

---

## ✏️ Customising the site

All content is in `index.html`. Key spots to update:

| What | Where in index.html |
|------|---------------------|
| Your name / title | `#hero` section |
| About me text | `#about` section |
| Skills | `#skills` section |
| Work experience | `#experience` section |
| Projects | `#projects` section |
| Education | `#education` section |
| Contact links | `#contact` section |
| GitHub link | Add to `.contact-links` in `#contact` |

---

## 📁 File structure

```
portfolio/
├── index.html       ← entire site (single file)
├── netlify.toml     ← Netlify routing config
└── README.md        ← this file
```

---

Built with pure HTML, CSS, and vanilla JS — zero dependencies, no build step.
