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
- `hackathon.qmd`: Winning-team case study with focal employer, peer benchmarks, methods, and recognition.
- `population.qmd`: Clearly dated 2026 reconstruction with holdout results.
- `cv.qmd`: Education, experience, certifications, and CV links.
- `contact.qmd`: Email and professional profiles.
- `assets/Annabella-Xu-Resume.pdf`: Exact copy of the latest resume exported natively from Pages to `Desktop/work/Annabella Xu Resume - job.pdf` on 19 November 2026.
- `styles.css`: Responsive visual design.
- `about.qmd`: Compatibility page for the previous About URL.

The diagrams on the project overview illustrate workflows and analytical categories. The Hackathon case study reuses the original aggregate sample-size figure from the final analytical package and links the supplied certificate unchanged. The population validation chart and metrics come from the report and R results reconstructed on 18 November 2026. Those results are explicitly distinguished from the original 2023 team project.

Content evidence: supplied resume; `MilkDragon.pptx`; winning-team certificate; Hackathon `final_submission` method notes and sample-size outputs; Ontario reconstruction report and `results/model_metrics.csv`. The original slide deck, source CSV records, employee-review excerpts, and private working files are not published. No rank beyond membership of a winning team is claimed.

## Assignment packaging

The submission ZIP contains `static-website/`, `source-code.zip`, and `submission-links.txt`. The source archive includes the Quarto files, style sheet, local assets, and publishing workflow, with no data files, credentials, Git history, caches, or virtual environments.
