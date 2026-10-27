# AutoCraft — download site

Static landing page for [AutoCraft](https://github.com/YOUR_USERNAME/AutoCraft), a no-code Minecraft mod studio. Ready for GitHub Pages.

## Publish on GitHub Pages

1. Create a GitHub repository (for example `autocraft-site`).
2. In `config.js` replace `YOUR_USERNAME` with your GitHub username (and repo name if different).
3. Upload `AutoCraft.exe` as a **GitHub Release** asset on the AutoCraft app repository, named exactly `AutoCraft.exe`.
4. Push this folder:

```bash
git init
git add .
git commit -m "AutoCraft download site"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/autocraft-site.git
git push -u origin main
```

5. Repo **Settings → Pages → Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: `main` / `/ (root)`
6. Site URL: `https://YOUR_USERNAME.github.io/autocraft-site/`

If the repo is named `YOUR_USERNAME.github.io`, the site is available at the domain root.

Do not commit the 80 MB exe into this repository. GitHub Pages is for the site; Releases are for the installer.
