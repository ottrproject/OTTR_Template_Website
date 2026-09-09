# OTTR for Websites!

Get started at [ottrproject.org](https://www.ottrproject.org/getting_started.html)! :tada:

The purpose of this template is to make maintaining a website on GitHub _less painful_. It is an OTTR website template built with R Markdown, designed to keep the source files easy to edit while automation handles routine quality checks and site rendering.

_This template helps you_:

- Write and edit website pages as [R Markdown files](https://rmarkdown.rstudio.com/), then render them as a static HTML site.
- Publish the rendered website from the repository's `docs/` directory, through [GitHub Pages](https://pages.github.com/).
- Use [GitHub Actions](https://www.ottrproject.org/customize-robots.html) to automate repetitive tasks after pull requests, including:
  - spelling checks with a project dictionary;
  - broken-link checks;
  - rendered-site previews; and
  - re-rendering the site after changes are merged to `main`.
- Keep authoring environments consistent with the [OTTR Docker image](https://hub.docker.com/repository/docker/jhudsl/base_ottr), helping teams avoid [dependency hell](https://en.wikipedia.org/wiki/Dependency_hell).
- Customize the site's pages, navigation, hosting, and visual style using the included guides.

[See the OTTR manuscript here!](https://www.tandfonline.com/doi/full/10.1080/26939169.2022.2118646)

<img src="https://docs.google.com/presentation/d/18k_QN7l6zqZQXoiRfKWzcYFXNXJJEo6j4daYGoc3UcU/export/png?id=18k_QN7l6zqZQXoiRfKWzcYFXNXJJEo6j4daYGoc3UcU&pageid=gf4fcf6569c_2_29" width="500" alt="OTTR workflow illustration" />

## What's included

- `index.Rmd` — the homepage template.
- `setup.Rmd` — instructions for enabling the repository's automated checks.
- `hosting.Rmd` — guidance for publishing the site with GitHub Pages.
- `editing.Rmd` — guidance for changing pages and site structure.
- `style.Rmd` and `styles.css` — guidance and files for customizing the visual design.
- `git_actions.Rmd` and `config_automation.yml` — documentation and configuration for the automated workflow.
- `_site.yml` — the site name, navigation, and rendering configuration.
- `docs/` — the rendered website that is ready to publish.

## To get started

- Visit [ottrproject.org](https://www.ottrproject.org/getting_started.html).
- Review the [rendered website template](https://ottrproject.org/OTTR_Template_Website/).
- Replace the sample content in `index.Rmd`, then update `_site.yml` with your website title and navigation.
- Work through the included Setup, Hosting, Editing, Style, and Git Actions pages to configure and publish your site.
- Use `resources/dictionary.txt` to add valid project-specific words that should pass spelling checks.
- See the repository's [license](LICENSE) for usage terms.
- If you encounter a problem or have an idea for improving this template, [open an issue](https://github.com/ottrproject/OTTR_Template_Website/issues/new/choose).
t
## Cheatsheet
Refer to our [cheatsheet](https://www.ottrproject.org/cheatsheets/ottr_website.html) for a quick reference on building your website with OTTR! 

## Contributing

Contributions are welcome. Please read the [OTTR contributing guide](https://github.com/ottrproject/.github/blob/main/CONTRIBUTING.md).
