# Repository Guidelines

## Project Structure & Module Organization

This repository is a dependency-free static site published with GitHub Pages.

- `index.html` contains all public page content and semantic structure.
- `styles.css` contains site-wide layout, typography, responsive rules, and print styles.
- `assets/images/` stores hosted images. Use subdirectories such as `logos/`, `research/`, or
  `publications/` if the collection grows.
- `docs/reference/` contains internal source material used to draft public content. Reference files
  are not automatically displayed on the site.
- `.nojekyll` tells GitHub Pages to serve the repository as plain static files.

There is no generated output directory or application framework. Keep the site lightweight unless
a documented requirement justifies adding tooling.

## Build, Test, and Development Commands

No build or dependency installation is required. Preview the site from the repository root:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000`. To find unfinished content, run:

```powershell
rg -n "placeholder|To be added|forthcoming" .
```

GitHub Pages deploys `main` from `/(root)` as described in `README.md`.

## Coding Style & Naming Conventions

Use two-space indentation in HTML and CSS. Prefer semantic HTML (`main`, `section`, `article`) and
retain accessible labels, descriptive alt text, visible focus states, and logical heading order.
Reuse the CSS custom properties defined in `:root` instead of introducing near-duplicate colors.

Name files with lowercase, descriptive, hyphen-separated names, such as
`assets/images/research/epidemic-model.webp`. Avoid spaces. Use SVG for logos and diagrams, WebP or
JPEG for photographs, and PNG only when transparency is needed.

## Testing Guidelines

There is no automated test suite. Before submitting changes, preview at desktop and mobile widths;
verify navigation anchors, image paths, keyboard focus, text contrast, and print layout. Confirm
that public copy contains no remaining placeholders or unverified claims.

## Commit & Pull Request Guidelines

History uses concise, sentence-case summaries describing one completed change, for example,
`Converted information from the image to a Markdown file for reference.` Keep each commit focused.

Pull requests should explain the purpose and content source, list verification performed, and link
related issues. Include before-and-after screenshots for visual changes. Flag unverified names,
citations, affiliations, or funding language explicitly.

## Public Content & Security

Everything published through GitHub Pages is public. Do not commit sensitive data, private contact
details, credentials, or restricted research material. Optimize large images before committing and
confirm that the organization has permission to publish them.
