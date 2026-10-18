# Birthday Website — GitHub Pages

This package is prepared for GitHub Pages (static hosting). It contains `index.html`, `letter.html`, and the `static/` assets folder.

## Deploy
1. Extract this ZIP.
2. Upload **all extracted contents** to the root of your GitHub repository (not the ZIP itself). Keep `index.html`, `letter.html`, and `static/` at the top level.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then click **Save**.
6. Wait for the Pages workflow to finish. The public URL will appear in Settings → Pages.

This version uses relative paths so it works from a GitHub project-page URL. It is static and does not require Flask, Render, `app.py`, or a `Procfile`.
