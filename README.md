# XBTASNP NCD2

React website for the XBTASNP NCD2 project.

## Run locally

```sh
npm ci
npm start
```

## Deploy to Netlify from GitHub

This repository includes `netlify.toml` with the production settings:

- Build command: `npm run build`
- Publish directory: `build`
- Client-side routes are served through `index.html` for direct navigation
  and refreshes.

In Netlify, choose **Add new site → Import an existing project**, connect
`Emitaz-pias/xbtasnpncd2`, and deploy the `main` branch. Netlify will build
the site on each push to that branch.
