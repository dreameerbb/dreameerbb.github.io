# Jaeheon Song — Personal Website

[Homepage](https://dreameerbb.github.io/) · [CV](https://dreameerbb.github.io/cv/) · [Notes](https://dreameerbb.github.io/blog/)

Research, projects, experience, and personal writing. This repository contains the static website served by GitHub Pages.

## Repository structure

| Path | Purpose |
| --- | --- |
| `docs/` | Static website served by GitHub Pages |
| `docs/index.html` | Homepage |
| `docs/cv/`, `docs/blog/` | CV and publicly published notes |
| `docs/_next/` | JavaScript, CSS, and fonts |
| `docs/images/`, `docs/published-assets/` | Images and public attachments |
| `docs/404.html`, `docs/404/` | Error pages |
| `docs/robots.txt`, `docs/sitemap.xml` | Search engine metadata |
| `docs/index.txt`, page-level `index.txt` files | Next.js navigation data |
| `docs/.nojekyll` | Preserves `_next/` files on GitHub Pages |
| `docs/_publication.json` | Automatic deployment verification |
| `.gitattributes` | Marks generated files in GitHub diffs |

GitHub Pages serves `/docs` from the `main` branch. Files inside `docs/` are generated and support navigation, equations, and images.

## Updates

Content and design are managed in [portfolio-manager](https://github.com/dreameerbb/portfolio-manager). Saving public changes automatically builds the website, pushes the generated files to GitHub, and deploys them to Pages. Administrative tools, databases, drafts, private notes, and reader email lists are excluded from this public repository. Private notes require a separate authentication service and authorization for each note.

Changes made directly to generated files are overwritten by the next publication. Edit the source project instead. This README and `.gitattributes` are maintained in `homepage/publishing/` in the source project.
