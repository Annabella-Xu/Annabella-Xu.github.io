# Annabella Xu Portfolio

A Quarto portfolio for AD688 M05 Participation 2, with About You, Projects, CV, and Contact pages.

## Preview and build

Install Quarto, then run from this folder:

```sh
quarto preview
quarto render
```

This site has no executable analysis blocks and requires no Python packages to render. Output is written to `_site/`. All illustrations and the downloadable PDF are stored locally in `assets/`.

## Publish

Push `main` to GitHub. The existing GitHub Actions workflow renders the site and publishes to `gh-pages`. In repository Settings > Pages, use the `gh-pages` branch and `/ (root)` if not already configured.

Expected website URL: https://annabella-xu.github.io/
Repository: https://github.com/Annabella-Xu/Annabella-Xu.github.io

## Content updates

- `index.qmd`: About You and professional interests.
- `projects.qmd`: Four academic/team project summaries.
- `cv.qmd`: Education, experience, certifications, and CV links.
- `contact.qmd`: Email and professional profiles.
- `assets/Annabella-Xu-Resume.pdf`: Downloadable resume, based on the supplied `Annabella Xu Resume - job.pdf`, with the C.H.I., Bank of Beijing, and Bloomberg dates corrected as requested.
- `styles.css`: Responsive visual design.
- `about.qmd`: Compatibility page for the previous About URL.

The project diagrams illustrate the described workflows and analytical categories; they are not charts of measured results. Project counts and experience are drawn from the supplied resume. No project repositories or performance metrics are invented.

## Assignment packaging

The submission ZIP contains `static-website/`, `source-code.zip`, and `submission-links.txt`. The source archive includes the Quarto files, style sheet, local assets, and publishing workflow, with no data files, credentials, Git history, caches, or virtual environments.
