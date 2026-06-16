# Central Meats — Devine Meats

This is a static website for Central Meats / Devine Meats.

## Files
- `index.html` — the homepage served by GitHub Pages
- `home.html` — original homepage source file
- `IMG-*.jpg` — product images used in the catalogue

## Deploying to GitHub Pages

1. Create a new GitHub repository.
2. In this folder, run:

```powershell
cd "c:\Users\ppp\OneDrive\website"
git init
git add .
git commit -m "Initial site commit"
```

3. Add the remote repository URL provided by GitHub:

```powershell
git remote add origin https://github.com/<your-username>/<repo-name>.git
```

4. Push the code:

```powershell
git branch -M main
git push -u origin main
```

5. In GitHub, go to **Settings** → **Pages**.
6. Under **Source**, choose `main` branch and `/ (root)` folder.
7. Save.

Your site will be available at `https://<your-username>.github.io/<repo-name>/` shortly.

## Notes
- If you want the site at the root without `/repo-name/`, use the repository name in the GitHub Pages URL only.
- If you buy a custom domain later, GitHub Pages can connect it via **Settings** → **Pages** → **Custom domain**.
