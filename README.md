# Jingjing Wei — Personal Profile Website

A bilingual (English / Chinese) static personal website, ready for GitHub Pages. English is the default language.

## Deploy with GitHub Pages

1. Create a new GitHub repository, for example `jingjing-wei.github.io` or `personal-website`.
2. Upload everything in this folder to the repository root: `index.html`, `.nojekyll`, and the `assets/` folder.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. GitHub will publish the site after the Pages deployment finishes.

If the repository is named `<username>.github.io`, the site will be available at `https://<username>.github.io/`. For a normal project repository, it will usually be available at `https://<username>.github.io/<repository-name>/`.

## Files

- `index.html` — the complete bilingual website
- `assets/profile.jpg` — profile photo, cropped only on the left/right sides; the full vertical image is preserved
- `.nojekyll` — ensures GitHub Pages serves the static files directly

No build step, framework, package manager, or external JavaScript dependency is required.
