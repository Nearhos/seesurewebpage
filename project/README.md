# Seesure Webpage

A React TypeScript application built with Vite.

## Development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Deploy to GitHub Pages

This project is configured for automatic deployment to GitHub Pages via GitHub Actions.

### Manual Deployment

If you want to deploy manually:

1. Install gh-pages: `npm install --save-dev gh-pages`
2. Run: `npm run deploy`

### Automatic Deployment

The project includes a GitHub Actions workflow (`.github/workflows/deploy.yml`) that automatically builds and deploys the site when you push to the main branch.

## Configuration

- **Base Path**: `/seesurewebpage/` (configured in `vite.config.ts`)
- **Build Output**: `dist/` directory
- **Custom Domain**: Configured via `public/CNAME`

## Features

- React 18 with TypeScript
- Vite for fast development and building
- Tailwind CSS for styling
- ESLint for code quality
- GitHub Pages deployment ready 