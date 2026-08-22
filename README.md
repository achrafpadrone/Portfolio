# Achraf Daou — Portfolio Site

Everything needed for the GitHub Pages site is in this folder.

## What's here

- `index.html` — the whole site (single file, no build step needed)
- `assets/Achraf-Daou-CV.pdf` — your CV, wired up to the "Download CV" button
- `assets/achraf-photo.jpg` — **not included yet, add this yourself** (see below)

## 1. Add your photo

The site already expects a photo at exactly this path:

```
assets/achraf-photo.jpg
```

Save your headshot with that exact name (must be `.jpg`) into the `assets` folder
before uploading, or upload it straight into `assets/` on GitHub afterwards — either
order works, the page will just show a placeholder "AD" monogram until the file
exists at that path.

## 2. Upload to GitHub (web UI, no terminal needed)

1. Open your existing repo on github.com.
2. Click **Add file → Upload files**.
3. Drag in `index.html`, the `assets` folder (with the CV and photo inside), and
   this `README.md`.
4. Commit directly to the `main` branch.

## 3. Turn on GitHub Pages

1. In the repo, go to **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Branch: **main**, folder: **/ (root)**. Save.
4. GitHub will give you a live URL, usually
   `https://achrafpadrone.github.io/<repo-name>/` — it can take a minute or two
   to go live the first time.

That's it — no build tools, no dependencies, it's a single static HTML file.
