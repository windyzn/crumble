# 🥐 Crumble

> Track the true cost of every bake.

Crumble is a single-page web app for home bakers who want to know exactly what their recipes cost — ingredient by ingredient, serving by serving.

## Features

- **Pantry** — store ingredients with store price, package size, unit, and optional brand/store name. Cost-per-unit is calculated automatically.
- **Recipes** — build recipes from your pantry ingredients, set a serving count, and get a full cost breakdown.
- **Cost summary** — total recipe cost, cost per serving, and three retail pricing options side by side (1.5×, 2.5×, 3.5× markup).
- **Persistent storage** — pantry and recipes are saved to `localStorage`, so everything is there when you come back.

## Tech

Plain HTML, CSS, and JavaScript — no framework, no build step. Fonts loaded from Google Fonts (requires internet connection).

## Local development

Just open `index.html` in your browser. No server needed.

```bash
open index.html
```

## Deploying to GitHub Pages

1. Make your changes to `index.html`
2. Commit and push to `main`:

```bash
git add index.html
git commit -m "describe your change"
git push
```

3. GitHub automatically rebuilds and deploys. Check the **Actions** tab in your repo to monitor deploy status.
4. Live at: `https://YOUR_USERNAME.github.io/crumble/`

## Roadmap / ideas

- [ ] Unit conversion (e.g. use oz in recipe when pantry item is in g)
- [ ] Custom markup percentage per recipe
- [ ] Print / export recipe cost sheet
- [ ] Multiple currency support
- [ ] Import/export pantry as CSV