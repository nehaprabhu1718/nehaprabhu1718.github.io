# Neha Prabhu's Personal Website

Personal website built with [Astro](https://astro.build), deployed to GitHub Pages.

## Project Structure

```
/
├── public/              # Static assets (favicon, images)
├── src/
│   ├── components/      # Reusable components (Navigation, Footer)
│   ├── layouts/         # Page layouts
│   ├── pages/           # Site pages
│   │   ├── index.astro  # Home page
│   │   ├── work.astro   # Work/experience page
│   │   ├── writing.astro # Articles/blog page
│   │   ├── projects.astro # Projects page
│   │   └── random.astro  # Miscellaneous page
│   └── styles/          # Global styles
└── .github/workflows/   # GitHub Actions for deployment
```

## Development

```bash
# Install dependencies
npm install

# Start development server at localhost:4321
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Deployment

This site is configured to deploy automatically to GitHub Pages when you push to the `main` branch.

### Setup GitHub Pages

1. Push this repository to GitHub as `nprabhu.github.io`
2. Go to Settings > Pages
3. Set Source to "GitHub Actions"
4. Push to `main` branch to trigger deployment

## Customizing Content

Edit the placeholder content in each page file:

- `src/pages/index.astro` - Home page intro and bio
- `src/pages/work.astro` - Work experience (edit the `experiences` array)
- `src/pages/writing.astro` - Articles/posts (edit the `articles` array)
- `src/pages/projects.astro` - Projects (edit the `projects` array)
- `src/pages/random.astro` - Personal interests, books, quotes

Update social links in:
- `src/components/Footer.astro` - GitHub, LinkedIn, email links
