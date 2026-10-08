# Mollie Williams, DrPH — AI in Public Health

An Astro recreation of [molliewilliamsdrph.com](https://molliewilliamsdrph.com), including the editorial home and about pages, the public-health AI impact assessment, and a personalized skill-plan builder.

## Local development

```sh
npm install
npm run dev
```

## Production build

```sh
npm run build
```

Astro writes the static site to `dist/`.

## Netlify

The included `netlify.toml` configures Netlify to run `npm run build` and publish `dist`. In Netlify, import this repository, keep the detected settings, and add the custom domain after the first successful deploy.

## Privacy

The assessment and skill builder run entirely in the visitor's browser. No answers are submitted or stored on a server.
