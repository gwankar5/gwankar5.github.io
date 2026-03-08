# Deploy to GitHub Pages

## Option A — Deploy from a branch
1. Create a repository, for example `POC`.
2. Upload these files to the repository root:
   - `index.html`
   - `styles.css`
   - `script.js`
3. On GitHub, open the repository.
4. Go to **Settings** → **Pages**.
5. Under **Build and deployment** → **Source**, choose **Deploy from a branch**.
6. Under **Branch**, select:
   - Branch: `main`
   - Folder: `/ (root)`
7. Save.
8. Wait for GitHub Pages to publish the site.

Your page will usually be available at:

`https://<username>.github.io/POC/`

## Option B — Use GitHub Actions
Use this if you later add a build step. In **Settings** → **Pages**, select **GitHub Actions** as the source and add a workflow.

## Notes
- Keep `index.html` at the repository root if you use branch deployment from `/ (root)`.
- For a project site, asset paths should be relative or tested under `/POC/`.
- In Pages settings, enable **Enforce HTTPS** after deployment.
