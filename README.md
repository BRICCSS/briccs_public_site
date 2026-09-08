# BRICCS public website

A lightweight, accessible public-facing website for the BRICCS research organization.

## Preview locally

No build tools or dependencies are required. Open `index.html` directly in a browser, or
serve the repository with any local static file server.

For example, if Python is installed:

```powershell
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Publish with GitHub Pages

1. Push the site to the repository's `main` branch.
2. Open the repository on GitHub and go to **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select `main`, choose `/(root)`, and save.

The `.nojekyll` file tells GitHub Pages to serve the site as plain static files.

## Updating content

The page is intentionally built without a framework. Edit the copy in `index.html` and
the visual styles in `styles.css`. Search for `placeholder` and square-bracketed text to
find content that still needs final organizational information.

## Reference material

- [BRICCSS research poster transcription](docs/reference/briccs-poster-transcription.md)
- [BRICCS organization structure](docs/reference/organization-structure.md)
- [Makoto Jones biosketch](docs/reference/makoto-jones-biosketch.md)
- [Makoto Jones: Contributions to Science](docs/reference/makoto-jones-contributions-to-science.md)
- [Makoto Jones: Influential Publications](docs/reference/makoto-jones-influential-publications.md)
- [Source poster photograph](assets/images/briccs_poster.jpg)
