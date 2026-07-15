# Alfred Portfolio

A minimal Astro portfolio prepared for GitHub Pages. Its visual system uses the
Benne typeface and the white, charcoal, and grey palette from the supplied
editorial reference.

## Personalize

Edit `src/pages/index.astro` to replace:

- the short biography;
- the current-work sentence;
- `hello@your-domain.com` with your email address.

Global colors, typography, spacing, and responsive behavior are in
`src/styles/global.css`.

## Add a project

Duplicate `src/content/projects/_template.md`, give the copy a short filename
such as `weather-app.md`, and replace its frontmatter and writing. The filename
becomes the project URL.

Set `draft: false` when the project is ready to appear on the Projects page.
Use `order` to control its position; lower numbers appear first. Delete the
included `portfolio.md` example whenever you no longer need it.

## Local development

```sh
npm install
npm run dev
```

## GitHub Pages

Push the `main` branch to GitHub, then select **GitHub Actions** as the Pages
source in the repository settings. The included workflow handles both project
repositories and repositories named `<username>.github.io`.
