# craigkahle.com

Personal site built with [Astro](https://astro.build) and Tailwind CSS v4, based on the Prima Persona theme by [Lexington Themes](https://lexingtonthemes.com). Deployed on Vercel on every push to `main`.

## Development

```
npm install
npm run dev       # local dev server
npm run build     # production build to ./dist/
npm run preview   # preview the build
```

## Structure

- `src/pages/`: routes (`index.astro` is the home page)
- `src/components/landing/`: home page sections (Intro, Work, Education, Socials)
- `src/components/fundations/`: shared building blocks (`Text`, `Button`, `Wrapper`, head/SEO)
- `src/styles/global.css`: Tailwind config and theme styles
- Work history lives in the `data` array in `src/components/landing/Work.astro`
