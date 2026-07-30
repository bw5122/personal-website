# Zhiwei (Berry) Wang — Academic Website

A fast, static academic website built with Hugo and the official
[PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme, configured for
deployment on Vercel.

## Local development

The site requires Hugo Extended 0.146.0 or newer.

```sh
hugo server
```

## Production build

```sh
hugo --gc --minify
```

## Deploy

Import the GitHub repository into Vercel. Vercel detects Hugo automatically and
deploys every push to the production branch, while pull requests receive preview
deployments.

## Content updates

Site-wide settings live in `hugo.yaml`. Page content lives in `content/`, and
the only small theme adjustment is in `assets/css/extended/custom.css`.

To publish the CV, add it as `static/cv.pdf`, then replace the email link in
`content/cv.md` with `/cv.pdf`.
