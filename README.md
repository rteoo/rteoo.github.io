# R. Teodoro — Public Work

<p align="center">
  <img src="assets/favicon.svg" width="128" alt="R. Teodoro — Public Work icon">
</p>

<p align="center">
  A static GitHub Pages profile for a curated set of original public repositories
  under rteoo, built only from public GitHub data.
</p>

This repository is the source of [rteoo.github.io](https://rteoo.github.io), a
static profile for a curated set of original public repositories under
[`rteoo`](https://github.com/rteoo). The page emphasizes inspectable work and
public contribution activity without pulling private contribution totals or
personal information into the site.

## Highlights

- A single Jekyll page on the `jekyll-theme-slate` theme, served by GitHub
  Pages from the `gh-pages` branch.
- Repository metadata from the public GitHub API only.
- Commit figures labeled as dated snapshots.
- The profile repository is listed but kept out of its own project-commit total.
- Progressive motion in JavaScript; the content stays readable without it.

## Public data boundary

- Repository metadata comes from the public GitHub API.
- Commit figures are dated snapshots from each public repository's contributor
  list and represent authored commits on its default branch.
- The profile repository is listed but excluded from the project-commit total,
  so edits to this site do not inflate the headline figure.
- Non-public repositories, anonymized non-public activity, and inferred personal
  details are out of scope.

## Structure

| Path | Purpose |
| --- | --- |
| `index.md` | Profile content and project index |
| `_layouts/default.html` | Document shell and metadata |
| `_config.yml` | Site title, description, URL, and theme |
| `assets/css/site.css` | Visual system and responsive behavior |
| `assets/js/site.js` | Progressive motion; the content works without it |
| `assets/favicon.svg` | The small public profile mark |

## Updating the profile

Refresh repository and commit figures from the public GitHub API before
changing them, and label each figure with its observation date. Preserve static
readability when JavaScript or motion is unavailable, and check the rendered
layout and links after a page change.

The repository records no standing publication workflow. Do not treat the live
site as changed until a publication and a live check have actually occurred.

## License

No license file is included.
