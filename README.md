# jubin-david.github.io

Personal portfolio website built with **React** (Create React App) and **Tailwind CSS**, deployed to **GitHub Pages**.

- **Live site**: `https://jubin-david.github.io`

## What’s inside

- **Landing/Banner**: intro + hero content (`src/components/banner/`)
- **Features**: highlight areas of work/strengths (`src/components/features/`)
- **Projects**: portfolio projects (`src/components/projects/`)
- **Resume**: experience, skills, education, achievements (`src/components/resume/`)
- **Testimonials**: testimonials slider (`src/components/tesimonial/`)
- **Contact**: contact section (`src/components/contact/`)
- **Layout**: navbar + footer (`src/components/navbar/`, `src/components/footer/`)

## Tech stack

- **React 18** + **Create React App** (`react-scripts`)
- **Tailwind CSS**
- **React Router** (`react-router-dom`)
- **Framer Motion** (animations)
- **react-slick / slick-carousel** (carousel)
- **gh-pages** (deployment)

## Getting started (local development)

### Prerequisites

- Node.js + npm

### Install

```bash
npm install
```

### Run locally

```bash
npm start
```

Then open `http://localhost:3000`.

## Scripts

- **`npm start`**: run dev server
- **`npm run build`**: create production build in `build/`
- **`npm test`**: run tests in watch mode
- **`npm run deploy`**: build + publish to GitHub Pages

## Deploying to GitHub Pages

This repo uses the `gh-pages` package. Deployment is configured via:

- `homepage` in `package.json` (currently `https://jubin-david.github.io`)
- `predeploy`: runs the production build
- `deploy`: publishes the `build/` directory

To deploy:

```bash
npm run deploy
```

## Project structure (high level)

```text
src/
  components/        UI sections (banner, features, projects, resume, contact, etc.)
  constants/         Shared data/constants used by the UI
  assets/            Images/icons exports
  App.js             Top-level app composition
  index.js           React entry point
  index.css          Global styles (Tailwind entry)
public/              Static assets
```

## Updating content

- **Text/content**: typically lives in `src/constants/` and section components under `src/components/`
- **Images**: add to `src/assets/` or `public/` (depending on how you reference them)

## License

All rights reserved (personal site). If you want to reuse parts, open an issue first.
