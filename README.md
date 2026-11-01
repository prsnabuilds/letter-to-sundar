# Letter to Sundar

A scroll-driven birthday letter. The title fades, a wax-sealed envelope opens, and the letter slides out to be read.

- `site/` is the static site (plain HTML, CSS and JS, no build step).
- Edit the letter between the `LETTER CONTENT` comments in `site/index.html`.
- Every push to `main` deploys to Cloudflare Pages through `.github/workflows/deploy.yml`. It needs a `CLOUDFLARE_API_TOKEN` repository secret with Cloudflare Pages edit permission.
