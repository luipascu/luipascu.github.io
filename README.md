# Academic research website

A starter academic website built with [Quarto](https://quarto.org/) and designed for deployment with GitHub Pages.

## Local preview

1. Install Quarto: https://quarto.org/docs/get-started/
2. Open this folder in VS Code.
3. In a terminal, run:

   ```bash
   quarto preview
   ```

4. Edit the `.qmd` files and `styles.scss`.

## Publish with GitHub Pages

1. Create a GitHub repository and push these files to its `main` branch.
2. In the repository, open **Settings → Pages**.
3. Set the publishing source to **Deploy from a branch**, then select `gh-pages` and `/ (root)` after the first successful workflow run.
4. The GitHub Actions workflow in `.github/workflows/publish.yml` renders the site and publishes it to `gh-pages`.

For a personal site at `https://USERNAME.github.io`, name the repository exactly `USERNAME.github.io`. For a project site, the URL will normally include the repository name.

## Before publishing

Replace all bracketed placeholders, add verified publication/profile links, check dates and roles, and review the site carefully before making it public.
