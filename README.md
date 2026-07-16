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
such as `weather-app.md`, and replace its title, description, and URL. Clicking
the project on the site opens that URL directly.

Set `draft: false` when the project is ready to appear on the Projects page.
Use `order` to control its position; lower numbers appear first. Until then,
the Projects page remains empty.

## Local development

```sh
pnpm install
pnpm dev
```

## GitHub Pages

Push the `main` branch to GitHub, then select **GitHub Actions** as the Pages
source in the repository settings. The included workflow handles both project
repositories and repositories named `<username>.github.io`.
