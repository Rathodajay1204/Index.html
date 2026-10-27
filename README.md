# Ajay Rathod — Portfolio

A responsive, single-file portfolio built with semantic HTML, CSS custom properties, and a small progressive-enhancement script. It intentionally has no framework or runtime dependencies.

## Run locally

From the repository root:

```sh
python3 -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000). You can also open `index.html` directly in a browser.

## Personalize before publishing

Edit `index.html`:

- **Hero and about:** update the introduction to match your real background and goals.
- **Selected work:** replace the three clearly labeled concept studies with real projects, screenshots, and links. Do not present concept names as client work.
- **Contact:** replace `hello@example.com` and the location placeholder. Remove or replace any contact channel you do not use.
- **Social metadata:** update the title, meta description, and Open Graph description if your positioning changes.
- **Visuals:** the project previews are drawn with CSS and inline SVG, so they load without stock-image requests. Replace them with optimized project screenshots when you have them.

## Quality checks

The repository has no package manager or build step because the site is plain HTML/CSS/JavaScript. A GitHub Actions workflow runs Hallmark's static checks on `index.html` when changes are pushed or a pull request is opened. Responsive visual review should still be performed at mobile and desktop widths before launch.

## Design notes

The page follows Hallmark's editorial direction: warm paper, dark ink, a restrained slate accent, expressive serif display type, thin rules, responsive layouts, visible keyboard focus, and reduced-motion support. No metrics or testimonials are fabricated.
