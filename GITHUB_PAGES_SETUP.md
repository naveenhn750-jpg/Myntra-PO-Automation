# GitHub Pages Setup

This site is ready to publish on GitHub Pages.

## Folder to upload

Use this folder as the root of your GitHub repository:

- `index.html`
- `.nojekyll`
- `.github/workflows/deploy-pages.yml`

## Quick publish steps

1. Create a new public GitHub repository.
2. Upload all files from this folder into the repo root.
3. Push to the `main` branch.
4. In GitHub, open:
   - `Settings`
   - `Pages`
5. Under `Build and deployment`, select:
   - `Source: GitHub Actions`
6. Wait for the `Deploy GitHub Pages` workflow to finish.
7. Your site URL will look like:
   - `https://<your-github-username>.github.io/<repo-name>/`

## Notes

- This is a static site and is free on GitHub Pages.
- The repository will be public in the normal free setup.
- Uploaded Excel files are processed in the browser and are not automatically stored by the page.
