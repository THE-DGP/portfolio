# Dev Patel — portfolio

Plain HTML/CSS/JS. No build step, no dependencies (fonts load from Google Fonts).

```
index.html          the whole site (styles + scripts inline)
img/                photos
img/logos/          brand logos (AllEvents, Lincoln City FC, Post Office, Autotrader, Cake Box)
netlify.toml        Netlify config (publish this folder, cache images)
```

## Deploy on Netlify

**Fastest:** go to https://app.netlify.com/drop and drag this whole folder onto the page.

**From GitHub (auto-deploys on every push):**
1. `git init && git add . && git commit -m "Portfolio"`
2. Create a repo on GitHub and push to it.
3. Netlify → Add new site → Import an existing project → pick the repo.
4. Build command: leave empty. Publish directory: `.` → Deploy.

**CLI:** `npm i -g netlify-cli && netlify deploy --prod --dir .`

## Edit
- Contact details: search `dvvptl@gmail.com`, `ddevvedd`, `THE-DGP`, `447900646945` in index.html.
- Add a logo: drop the file in `img/logos/` and add it to the `LOGOS` map in index.html.
