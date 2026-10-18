contact us for an E-Wallet# xsupport

## Deploy to Netlify

This project is configured for Netlify deployment:

- Build command: `npm run build`
- Publish directory: `build`
- Single-page app routes are redirected to `index.html`, so routes such as
  `/cookie-policy` also work when opened directly or refreshed.

To deploy from GitHub, push this repository to GitHub, then create a new site
in Netlify and select the repository. Netlify will read these settings from
`netlify.toml` and build the site on each push.
