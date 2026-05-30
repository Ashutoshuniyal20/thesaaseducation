# The SaaS Education

A custom Hugo publication homepage for `thesaaseducation.com`.

## Local development

```powershell
npm install
npm run dev:css
hugo server
```

For a production build:

```powershell
npm run build
```

## Structure

```text
assets/css/              Source styles and Tailwind entry
content/posts/           Editorial content
layouts/_default/        Base, list, and article templates
layouts/partials/        Reusable SEO, navigation, card, and footer components
layouts/index.html       Homepage composition
static/                  Public assets
```

The site includes semantic landmarks, accessible controls, responsive layouts, dark mode, canonical URLs, Open Graph metadata, Twitter cards, JSON-LD, Hugo taxonomies, and sitemap support.

