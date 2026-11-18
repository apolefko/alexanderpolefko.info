# alexanderpolefko.info

Personal site. Plain HTML + CSS, served by GitHub Pages. No build step, no dependencies
(Google Fonts is the only external request, with system-font fallbacks).

- `index.html` — all content. Sections: §01 About, §02 Experience, §03 Shipped.
- `style.css` — parchment / field-manual theme. Colors are CSS variables at the top.
- `assets/` — headshot, favicon.
- `CNAME` — custom domain. `alexandermpolefko.info` redirects here from a separate repo.

## Adding a shipped project
Copy an `<li>` in the `.log` list under `#shipped`. Tag is a short uppercase word (TOOL, GAME, APP, POST).

## Deploy
Push to `main`. Pages rebuilds in about a minute.
