# jaxon-portfolio-site

Personal portfolio site for Jaxon Moffitt. Static HTML, built on the free
[iPortfolio](https://bootstrapmade.com/iportfolio-bootstrap-portfolio-websites-template/)
template by BootstrapMade (the footer credit links are required by its license).

## Structure

- `index.html`: home page (about, skills, resume, projects, contact)
- `project-*.html`: one details page per project
- `assets/css/custom.css`: site-specific styles layered on the template's `main.css`
- `assets/img/portfolio-projects/`: project screenshots

## Adding a project

1. Add a screenshot to `assets/img/portfolio-projects/`.
2. Copy the project card block in the `#portfolio` section of `index.html`.
3. Copy `project-mapping-tool.html` to `project-<name>.html` and update it.

## Preview locally

Open `index.html` in a browser, or run `python -m http.server` and visit http://localhost:8000.

## Hosting

Works as-is on GitHub Pages: Settings > Pages > Deploy from branch `main`, folder `/ (root)`.
