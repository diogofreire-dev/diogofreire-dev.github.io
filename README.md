# diogofreire-dev.github.io

My personal portfolio: who I am, the projects I've built and how to reach me.

Live at **https://diogofreire.is-a.dev/** (custom domain from [is-a.dev](https://is-a.dev), set in the `CNAME` file).

## How it's built

- Plain HTML and CSS, written by hand. No framework and no build step, so GitHub Pages serves the files exactly as they are in the repo.
- No third-party requests (no web fonts, analytics or CDNs). That keeps the page fast and lets the Content Security Policy in `index.html` allow only `'self'`.
- Light and dark themes follow the visitor's system setting through `prefers-color-scheme`.
- `.nojekyll` tells GitHub Pages to skip Jekyll, since there is nothing for it to build.
- Skill logos in `assets/icons/` come from [Simple Icons](https://simpleicons.org/) (CC0); the generic ones (database, cloud, lock, key, flag) are drawn by hand.

## Run it locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.
