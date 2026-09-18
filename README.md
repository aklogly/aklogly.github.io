# jloganlyle.com

Personal site for Logan Lyle — professional hub, selected work, and the public
homepage/privacy policy for the Simon (Chief of Staff) Google OAuth app.

Built with [Astro](https://astro.build) as a static site, deployed to GitHub Pages
under the custom domain `jloganlyle.com`.

## Structure

```
src/
  layouts/BaseLayout.astro   shared page shell (nav, footer, meta)
  components/                Nav, Footer
  pages/                     one .astro file per route
  styles/global.css          design tokens + shared styles
public/                      static assets, CNAME
```

Pages marked with a `needs-input` badge in the rendered page contain placeholder
copy pending explicit approval — see the redesign brief for context before
publishing.

## Local development

```
npm install
npm run dev       # http://localhost:4321
npm run build     # outputs to dist/
```

## Deployment

GitHub Pages, deployed from `main`. Do not merge to `main` without review.
