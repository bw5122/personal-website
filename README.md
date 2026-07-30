# Zhiwei (Berry) Wang — Academic Website

A fast, static academic website built with Astro and configured for deployment on Vercel.

## Local development

```sh
npm install
npm run dev
```

## Production build

```sh
npm run build
```

## Deploy

Import the GitHub repository into Vercel. Vercel detects Astro automatically and deploys every push to the production branch, while pull requests receive preview deployments.

## Content updates

The homepage content lives in `src/pages/index.astro`, and the visual styling lives in `src/styles/global.css`.

To publish the CV, add it as `public/cv.pdf`, then replace the current “Request CV” link with `/cv.pdf`.
