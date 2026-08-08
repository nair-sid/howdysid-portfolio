# Sibharth Nair — Portfolio

Static site, no build step. Structure:

```
index.html                        → main site
styles/main.css                   → all styles (shared design tokens)
script.js                         → nav toggle, scroll effects, reveal animations
assets/                           → put profile.jpg here
projects/
  drop-off-backlog/index.html     → The Drop-Off Backlog (RICE + MoSCoW artifact)
```

## Before you push this live, edit these

**index.html**
- [ ] Hero paragraph (`.hero-sub`) — replace the bracketed placeholder with your real 2–3 sentence intro
- [ ] Swap the `SN` avatar monogram for a real photo (see `assets/README.txt`)
- [ ] LinkedIn URL in the Contact section
- [ ] Email address in the Contact section
- [ ] Phone number in the Contact section (or delete that `.contact-item` block if you'd rather not list it)
- [ ] The two placeholder project cards ("Planned" / "Idea") — rename, or delete if you don't want to tease unfinished work yet
- [ ] `.section-count` text ("1 live · 2 planned") if you change the number of cards

**projects/drop-off-backlog/index.html**
- Untouched except for one addition: a small "← Portfolio" link (top-left) pointing back to `index.html#backlog`.

## Adding your next artifact

1. Make a new folder: `projects/your-project-name/`
2. Put a self-contained `index.html` in it (same pattern as the drop-off-backlog one)
3. In the main `index.html`, duplicate one of the `.project-card` blocks in `#backlog`, point its `href` at `projects/your-project-name/index.html`, and change `data-status` to `"live"`

## Deploying to GitHub Pages

1. Create a new GitHub repo (e.g. `your-username.github.io` for a root domain, or any name for a project site)
2. Push this whole folder to the repo root:
   ```
   git init
   git add .
   git commit -m "Portfolio site"
   git branch -M main
   git remote add origin https://github.com/your-username/your-repo.git
   git push -u origin main
   ```
3. In the repo: **Settings → Pages → Source → Deploy from branch → `main` / `root`**
4. Your site goes live at `https://your-username.github.io/your-repo/` (or your custom domain if you set one up)
