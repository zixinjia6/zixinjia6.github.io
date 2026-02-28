# Personal Portfolio (GitHub Pages)

This is a static personal website template designed for GitHub Pages.

## Quick customize

1. Open `index.html` and replace:
- `Your Name`
- intro/about text
- project titles + links
- email/GitHub/LinkedIn links
2. Put your resume at `assets/resume.pdf`.

## Deploy to GitHub Pages (`username.github.io`)

### Option A (recommended): user site
Use repository name exactly: `username.github.io`

1. Create a GitHub repo named `username.github.io`.
2. In this folder, run:

```bash
git init
git add .
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin https://github.com/username/username.github.io.git
git push -u origin main
```

3. On GitHub: `Settings` -> `Pages` -> `Build and deployment`
- Source: `Deploy from a branch`
- Branch: `main` and `/ (root)`

Your site URL will be:
`https://username.github.io`

### Option B: project site
If repo name is not `username.github.io`, your URL becomes:
`https://username.github.io/repo-name`

For this template, Option A is simpler.

## Local preview

Double click `index.html`, or run a local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
